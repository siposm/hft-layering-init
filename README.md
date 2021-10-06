# hft-layering-init

#### Steps:

1. create `BlogSystem.Data` layer with `.mdf` `.ldf` files (already seen in the previous lesson)
1. create `BlogSystem.UI` layer (Console Application) and add small test to make sure if DB works correctly
1. add following layers / projects as class libraries
    - BlogSystem.Repository
    - BlogSystem.Logic
    - BlogSystem.Tests
1. `BlogSystem.Repository` layer
    - add reference to data layer
    - create interfaces and classes
1. `BlogSystem.Logic` layer
    - add reference to data + repo
    - create interfaces and classes
1. `BlogSystem.UI` layer
    - add reference to logic and repo
    - write codes to use logic's functionalities

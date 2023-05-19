# CircleCI Learning Note
   * 官网参考
      + [Welcome to CircleCI Documentation](https://circleci.com/docs/)<br>
      + [CircleCI Overview](https://circleci.com/docs/2.0/about-circleci/#section=getting-started)<br>
      + Examples - 使用的例子，可以根据例子学习<>
         - [Open Source Projects that use CircleCI](https://circleci.com/docs/2.0/example-configs/)<br>
         - [Database Config Examples](https://circleci.com/docs/2.0/postgres-config/)<br>
         - [Sample config.yml Files](https://circleci.com/docs/2.0/sample-config/)<br>
         - [Tutorials and Sample Apps](https://circleci.com/docs/2.0/tutorials/)<br>
         - [Using Orbs](https://circleci.com/docs/2.0/using-orbs/)<br>
# Getting Started Introduction
   * [Getting Started Introduction](https://circleci.com/docs/2.0/getting-started/)<br>
      + 步骤
         1. Adding a .yml File  - 关于 YAML 参考 [YAML](https://en.wikipedia.org/wiki/YAML)<br>
         ```yaml

           version: 2
           jobs:
             build:
               docker:
                 - image: circleci/ruby:2.4.1
               steps:
                 - checkout
                 - run: echo "A first hello"

         ```
         2. Setting up Your Build on CircleCI
            1. Sign up a CircleCI Account
               - 选择 【Sign up With Bitbucket】
               - Create a unique username for Bitbucket Cloud
                  * bitbucket.org / wanglai
               - 后续，创建项目或导入项目



#
#

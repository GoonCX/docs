docs
====

```ASCII
   ____      ___      ___    __   __        ____   __    __
  //  ''    // \\    // \\   ||\\ ||       //  ''   \\  //
 ||        ||   ||  ||   ||  || \\||  ==  ||         \\//
 ||  ==||  ||   ||  ||   ||  ||  \\|      ||         //\\
  \\__//    \\_//    \\_//   ||   ||       \\__,,  ,//  \\,

```

####(Go on Continuous Delivery, Monitoring and infrastructure orchestration)

GoonCX is a distributed continuous delivery, deployment, monitoring and orchestration platform hopefully to be built on containers using GoLang.

This repository is for the issues tracking and misc documentation

###Preface
The reason for a new kind of infrastructure orchestration, monitoring and other related activities - is that, we need to install an agent for everything in today's world. So for every kind of system we need its agent on the machine. Then we manage those agents using configuration management tools and then it just becomes way too complicated to handle all these various type of common activities which include CI, Monitoring and alerting, peformance measurement.

###Enter GoonCX
We are proposing a light weight server client interaction, where client sits on local machine and reports to server using plugins in terms of monitoring, alerting and configuration management. We can use existing opensource software to comply with underlying well defined clients, later we can also create something which runs independently. Go gives us advantage for providing binaries and no need to install additional software in terms of other popular configuration management tools.

On a very basic primise Go looks like this

```ASCII

      __________________                __________________
     | Goon Server      | ------------>| Goon client      |
      ------------------                ------------------

```






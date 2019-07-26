![Aloha Project Logo](https://raw.githubusercontent.com/estradav/aloha/master/images/AP_horizontal.png)
***

- [Why Git?](https://github.com/estradav/aloha#why-git)
- [Setting up the stack](https://github.com/estradav/aloha#setting-up-the-stack)
  - [Basic stack](https://github.com/estradav/aloha#-basic-stack)
  - [Vagrant stack](https://github.com/estradav/aloha#-vagrant-stack)
  - [Docker stack](https://github.com/estradav/aloha#-docker-stack)
- [Challenges](https://github.com/estradav/aloha#challenges)
- [Points System](https://github.com/estradav/aloha#points-system)
- [Credits](https://github.com/estradav/aloha#credits)

# Welcome to Aloha Project! <img src="https://img.icons8.com/doodle/48/000000/hello.png">

Hello applicant! With this test you will be able to demonstrate your skills to be a member of our **fantastic** work group.

Below you will see the technologies that will be used to assess your skills and that are required for your next **big job**.

Don't forget it's a **competition**, so show us your best version and good luck! :wink:

### Stack
<table>
  <tr>
    <td></td>
    <td><b>Technology</b></td>
    <td><b>Description</b></td>
    <td><b>Required</b></td>
  </tr>
  <tr>
    <td><img src="https://img.icons8.com/color/48/000000/virtualbox.png"></td>
    <td><a href="https://www.virtualbox.org"><b>VirtualBox</b></a></td>
    <td>Virtualization software</td>
    <td><b>If you don't want extra points, it's essential</b></td>
  </tr>
  <tr>
    <td><img src="https://cdn.iconscout.com/icon/free/png-48/1174986.png"></td>
    <td><a href="https://www.vagrantup.com"><b>Vagrant</b></a></td>
    <td>Development environment</td>
    <td rowspan="2"><b>If you want Extra Points, use either of the two</b></td>
  </tr>
  <tr>
    <td><img src="https://img.icons8.com/color/48/000000/docker.png"></td>
    <td><a href="https://www.docker.com"><b>Docker</b></a></td>
    <td>Container platform</td>
  </tr>
  <tr>
    <td><img src="https://img.icons8.com/color/48/000000/linux.png"></td>
    <td><a href="https://www.linux.org"><b>Linux</b></a></td>
    <td>Operating system</td>
    <td><b>Essential</b></td>
  </tr>
</table>

### Tools
<table>
  <tr>
    <td></td>
    <td><b>Technology</b></td>
    <td><b>Description</b></td>
    <td><b>Required</b></td>
  </tr>
  <tr>
    <td><img src="https://img.icons8.com/color/48/000000/git.png"></td>
    <td><a href="https://www.git-scm.com"><b>Git</b></a></td>
    <td>Distributed version-control system</td>
    <td><b>Essential</b></td>
  </tr>
  <tr>
    <td><img src="https://img.icons8.com/officel/48/000000/database.png"></td>
    <td><a href="https://en.wikipedia.org/wiki/SQL"><b>SQL</b></a></td>
    <td>Programming language</td>
    <td><b>Essential</b></td>
  </tr>
  <tr>
    <td><img src="https://img.icons8.com/dusk/48/000000/php-logo.png"></td>
    <td><a href="https://www.php.net"><b>PHP</b></a></td>
    <td>Programming language</td>
    <td><b>Essential</b></td>
  </tr>
  <tr>
    <td><img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/194_Laravel_logo_logos-48.png"></td>
    <td><a href="https://laravel.com"><b>Laravel</b></a></td>
    <td>Web framework</td>
    <td><b>If you want Extra Points, make <a href="">laravel-crud</a></b></td>
  </tr>
  </tr>
</table>

# Why Git?
> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. <br>
>
> Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

Also... Git is a fun system that will help you to organize all the changes of your projects and the best of all is that you will never lose anything!

So, keep in mind that all challenges for **Aloha Project** must be **forked** and **pushed** into **private repositories** of your GitHub profile. Then, you only have to add the user [**estradav**](https://github.com/estradav) as collaborator of your repositories to visualize your code.

### Example: yourgithubusername Repositories

- Repository: [yourgithubusername](https://github.com/estradav) / **[sql-querys]()** *forked from* <a href="https://github.com/estradav">estradav / <b>aloha</b></a><br>
- Repository: [yourgithubusername](https://github.com/estradav) / **[laravel-crud]()** *forked from* <a href="https://github.com/estradav">estradav / <b>aloha</b></a><br>
- Repository: [yourgithubusername](https://github.com/estradav) / **[php-algorithms]()** *forked from* <a href="https://github.com/estradav">estradav / <b>aloha</b></a>

# Setting up the stack

> Pssssst! Basic stack is boring :sleeping:

As you know, everyone needs a home for their projects and you are no exception, so you must decide the environment where your repositories will run.

The use of these technologies has a reason and it's very simple, **DevOps**. **DevOps** is a set of practices that automates the processes between software development and IT teams, so they can build, test, and release software faster and more reliably.

<b>NOTE: Just like your repositories, your environments must also be backed up and shared. Therefore, it is VERY IMPORTANT that you send the image of your environment to the email address that contacted you. In case you have chosen <a href="https://www.docker.com">Docker</a> as Stack, simply load your container to <a href="https://hub.docker.com">Docker Hub</a> and send us the web address of the container by e-mail.</b>

## <img src="https://img.icons8.com/color/48/000000/virtualbox.png"> Basic stack

> Oracle VM VirtualBox is a cross-platform virtualization application. What does that mean? For one thing, it installs on your existing Intel or AMD-based computers, whether they are running Windows, Mac OS X, Linux, or Oracle Solaris operating systems (OSes). Secondly, it extends the capabilities of your existing computer so that it can run multiple OSes, inside multiple virtual machines, at the same time. As an example, you can run Windows and Linux on your Mac, run Windows Server 2016 on your Linux server, run Linux on your Windows PC, and so on, all alongside your existing applications. You can install and run as many virtual machines as you like. The only practical limits are disk space and memory.

Okay, this election is boring :disappointed:, but it doesn't matter. Your next steps are:

- Install Linux in the virtual machine
- Fork and download all the repositories we shared you
- Solve as many challenges as you can

**NOTE: Don't forget commit and push your changes to your repositories.**

## <img src="https://cdn.iconscout.com/icon/free/png-48/1174986.png"> Vagrant stack

> Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past.

Vagrant is amazing, it helps you automate development environments, now developers should just worry about having fun in their favorite code editor. So if this is your choice, congrats. Your next steps are:

- Create Vagrantfile
- Install a Linux Vagrant box
- Fork and download all the repositories we shared you
- Solve as many challenges as you can

**NOTE: Don't forget! This gives you Extra Points. Also... commit and push your changes to your repositories.**

## <img src="https://img.icons8.com/color/48/000000/docker.png"> Docker stack

> Docker is a platform for developers and sysadmins to develop, deploy, and run applications with containers. The use of Linux containers to deploy applications is called containerization. Containers are not new, but their use for easily deploying applications is.

Containers help you deploy applications quickly; best of all, they're less complex and consume fewer machine resources. So if this is your choice, congrats. Your next steps are:

- Install Linux container
- Fork and download all the repositories we shared you
- Solve as many challenges as you can

**NOTE: Don't forget! This gives you Extra Points. Also... commit and push your changes to your repositories.**

# Challenges

 - <img src="https://img.icons8.com/flat_round/30/000000/question-mark.png"> [Q&A Test](https://github.com): It is made up of some technical questions about computer science and programming languages. 
 - <img src="https://img.icons8.com/color/30/000000/linux.png"> [Linux Test](https://github.com): Exercise your hacker fingers, let's blow up the console!
 - <img src="https://img.icons8.com/officel/30/000000/database.png"> [SQL Test](https://github.com) : Oh... does it look like it's time to start playing with data?
 - <img src="https://img.icons8.com/dusk/30/000000/php-logo.png"> [PHP Algorithms Test](https://github.com): Put your imagination to flight and solve as many challenges as you can.
 - <img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/194_Laravel_logo_logos-32.png"> [Laravel Test](https://github.com): Now is time to finish! Let's go to create a CRUD in Laravel with Authentication.

# Points System

The points system evaluates each of the exercises you answer. Each exercise solved correctly will have a fixed amount of points and if you solve exercises that provide extra points, the amount of points accumulated will increase.

**It is very important that you know that this test provides a great percentage of progress for your application, but it does not define completely that you are selected.** 

# Credits

Thank you at following CDNs for the images of this repository.

- [**Icons8**](https://icons8.com/)
- [**Iconscout**](https://iconscout.com/)
- [**Iconfinder**](https://www.iconfinder.com/)

Made with :green_heart: by [**CI Estrada Velasquez**](https://www.estradavelasquez.com/)

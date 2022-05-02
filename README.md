![](/extras/images/Success.png)

###### <i>Recent Update on 03/05/2022.</i>
• Finished the project.

###### <i>Old Update on 02/05/2022.</i>
• Started the project.

## Subject:

You can find the subject of this project [here.](https://github.com/Olbrien/42Lisboa-lvl_1_born2beroot/blob/main/extras/lvl_1_born2beroot.pdf)

![](/extras/images/gif1.gif)

## How to run:

Download the repository.

## Useful Links:

[sigaction video](https://youtu.be/_1TuZUbCnX0)

## Research:

<code>

Graphical User Interface (GUI) and Command Line Interface (CLI):

    Interface:

        A user interface, consisting of the set of dials, knobs, operating system commands,
        graphical display formats, and other devices provided by a computer or a program to
        allow the user to communicate and use the computer or program. A graphical user
        interface (GUI) provides its user a more or less "picture-oriented" way to interact
        with technology. A GUI is usually a more satisfying or user-friendly interface to a
        computer system.

    Graphical User Interface (GUI):

        A graphical user interface (GUI) is a type of user interface through which users interact
        with electronic devices via visual indicator representations.
        It was designed as a response to the problem of inefficient usability in early, text-based
        command-line interfaces for the average user.

    Command Line Interface (CLI):

        Command Line Interface connects a user to a computer program or operating system.
        Through the CLI, users interact with a system or application by typing in text
        (commands). The command is typed on a specific line following a visual prompt from
        the computer. The system responds to the text, and the user may then type on the next
        command line that appears. Through this command and response interaction, the user is
        able to issue a series of commands, which are executed by the system or program.

---------------------------------------------------------------------------------------------

Operating System:

    What is an Operating System:

        An Operating System (OS) is a software that acts as an interface between computer
        hardware components and the user. Every computer system must have at least one
        operating system to run other programs. Applications like Browsers, MS Office,
        Notepad, Games, etc., need some environment to run and perform its tasks.

        The OS helps you to communicate with the computer without knowing how to speak
        the computer’s language. It is not possible for the user to use any computer or
        mobile device without having an operating system.

    Examples of Operating System:

        - Windows
        - Android
        - iOS
        - Mac OS
        - Linux
        - Chrome OS

    Functions of Operating System:

        Process management:
            Process management helps OS to create and delete processes.
            It also provides mechanisms for synchronization and communication among processes.

        Memory management:
            Memory management module performs the task of allocation and de-allocation of
            memory space to programs in need of this resources.

        File management:
            It manages all the file-related activities such as organization storage,
            retrieval, naming, sharing, and protection of files.

        Device Management:
            Device management keeps tracks of all devices. This module also responsible
            for this task is known as the I/O controller. It also performs the task
            of allocation and de-allocation of the devices.

        I/O System Management:
            One of the main objects of any OS is to hide the peculiarities of that hardware
            devices from the user.

        Secondary-Storage Management:
            Systems have several levels of storage which includes primary storage,
            secondary storage, and cache storage. Instructions and data must be stored in
            primary storage or cache so that a running program can reference it.

        Security:
            Security module protects the data and information of a computer system against
            malware threat and authorized access.

        Command interpretation:
            This module is interpreting commands given by the and acting system resources
            to process that commands.

        Networking:
            A distributed system is a group of processors which do not share memory,
            hardware devices, or a clock. The processors communicate with one another
            through the network.

        Job accounting:
            Keeping track of time & resource used by various job and users.

        Communication management:
            Coordination and assignment of compilers, interpreters, and another software
            resource of the various users of the computer systems.

    Advantage of Operating System:

        - Allows you to hide details of hardware by creating an abstraction.
        - Easy to use with a GUI.
        - Offers an environment in which a user may execute programs/applications.
        - The operating system must make sure that the computer system convenient to use.
        - Operating System acts as an intermediary among applications and the hardware components.
        - It provides the computer system resources with easy to use format.
        - Acts as an intermediator between all hardware’s and software’s of the system.

    Disadvantages of Operating System

        - If any issue occurs in OS, you may lose all the contents which have been stored
        in your system.
        - Operating system’s software is quite expensive for small size organization which
        adds burden on them. Example Windows.
        - It is never entirely secure as a threat can occur at any time.

    What is Kernel in Operating System:

        The kernel is the central component of a computer operating systems. The only job
        performed by the kernel is to the manage the communication between the software
        and the hardware. A Kernel is at the nucleus of a computer. It makes the
        communication between the hardware and software possible. While the Kernel is the
        innermost part of an operating system, a shell is the outermost one.

    https://www.guru99.com/operating-system-tutorial.html

---------------------------------------------------------------------------------------------

Debian:

    Debian is a free operating system (OS) for your computer. An operating system is the set
    of basic programs and utilities that make your computer run. Debian uses the kernel Linux
    (the kernel is the core of an OS), but most of the basic OS tools come from the GNU project.
    Thus we refer to Debian as a Debian GNU/Linux operating system, giving credit to all its
    main originators. Debian GNU/Linux provides much more than just the OS---a wide range of
    application software is included too. It comes with a total of over 51000 packages,
    precompiled software bundled up in a nice format for easy installation on your machine.

    https://wiki.debian.org/DebianIntroduction


AppArmor:

    AppArmor is an effective and easy-to-use Linux application security system. AppArmor
    proactively protects the operating system and applications from external or internal
    threats, even zero-day attacks, by enforcing good behavior and preventing both known and
    unknown application flaws from being exploited.

    AppArmor is a Mandatory Access Control framework. When enabled, AppArmor confines programs
    according to a set of rules that specify what files a given program can access. This
    proactive approach helps protect the system against both known and unknown vulnerabilities.

    https://wiki.apparmor.net/

    If you are using Debian 10 "Buster" or newer, AppArmor is enabled by default.

    https://wiki.debian.org/AppArmor/HowToUse


SELinux:

    Security-Enhanced Linux (SELinux) is a security architecture for Linux® systems that
    allows administrators to have more control over who can access the system.

    https://www.redhat.com/en/topics/linux/what-is-selinux


Apt and Aptitude:

    Aptitude and apt-get are two of the popular tools which handle package management. Both
    are capable of handling all kinds of activities on packages including installation,
    removal, search etc.

        apt-get install docker-compose
        apt-get remove docker-compose

        aptitude install wget -y
        aptitude search python


    What is Apt:

        Apt or Advanced Packaging Tool is a free and open source software which gracefully
        handles software installation and removal.

        Apt is whole command line with no GUI. Whenever invoked from command line along
        with specifying the name of package to be installed, it finds that package in configured
        list of sources specified in ‘/etc/apt/sources.list’ along with the list of dependencies
        for that package and sorts them and automatically installs them along with the current
        package thus letting user not to worry of installing dependencies.


    What is Aptitude:

        Aptitude is front-end to advanced packaging tool which adds a user interface to
        the functionality, thus allowing a user to interactively search for a package and
        install or remove it.

        Aptitude is a higher-level package managers that abstracts low level details, and
        can operate in both text-based interactive UI mode and even in command line
        non-interactive mode.


    https://www.tecmint.com/difference-between-apt-and-aptitude/


Secure Shell (SSH):

    It's a network communication protocol that enables two computers to communicate and share
    data. An inherent feature of ssh is that the communication between the two computers is
    encrypted meaning that it is suitable for use on insecure networks.

    SSH is often used to "login" and perform operations on remote computers but it may also
    be used for transferring data.


Firewall:

    In computing, a firewall is a network security system that monitors and controls incoming
    and outgoing network traffic based on predetermined security rules. A firewall typically
    establishes a barrier between a trusted network and an untrusted network, such as the
    Internet.


Uncomplicated Firewall (UFW):

    Uncomplicated Firewall (UFW) is a program for managing a netfilter firewall designed to
    be easy to use. It uses a command-line interface consisting of a small number of simple
    commands, and uses iptables for configuration. UFW is available by default in all Ubuntu
    installations after 8.04 LTS.


Logical Volume Manager (LVM):

    Logical volume management provides a higher-level view of the disk storage on a computer
    system than the traditional view of disks and partitions. This gives the system
    administrator much more flexibility in allocating storage to applications and users.

    https://wiki.debian.org/LVM


---------------------------------------------------------------------------------------------


---------------------------------------------------------------------------------------------



---------------------------------------------------------------------------------------------


</code>

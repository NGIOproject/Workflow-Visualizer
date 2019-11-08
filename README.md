# Workflow Visualizer Prototype

This graphical user interface displays a timeline of batch system jobs and their individual steps.
This can be used to get an overview of complex jobs and can show bottleneck job steps.
The visualizer is just a prototype which will not be further improved.
Further development of the Workflow-Visualizer happens within the [Vampir](https://vampir.eu/) project.

This software was developed as part of the EC H2020 funded project NEXTGenIO (Project ID: 671951) http://www.nextgenio.eu.

## Download
The binary of the prototype can be downloaded [here](https://cloudstore.zih.tu-dresden.de/index.php/s/m73A37xAnPF6ep2) and works on x86_64 Linux operating systems.

## How to execute

    ./workflow-gui

When a directory is specified, the subdirectories will be searched for `job_log.json` files.
All of the found job information files will be opened and shown.

    ./workflow-gui <path-to-workflow-tracing-folder>

A detailed description of the GUI can be found in [WorkflowVisualizer.md](doc/WorkflowVisualizer.md).
Workflow traces can be created using [JobLog](https://github.com/NGIOproject/JobLog) and [otf2_cli_profile](https://github.com/NGIOproject/otf2_cli_profile).


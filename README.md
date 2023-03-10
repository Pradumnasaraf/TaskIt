## TaskIt

It is a simple task manager that allows you to create, edit, delete and list tasks from the command line. It is built with Go and Cobra.

![taskit demo gif](https://user-images.githubusercontent.com/51878265/223354705-ca2fa9c9-b054-450e-9a0b-60751c3f8ee1.gif)

### ⭐️ Features

- Adding tasks
- Deleting a task
- Updating tasks
- Completing tasks
- Deleting all tasks
- Listing all tasks

### ❗️ Prerequisites

- Have Go installed on your machine and have the basic knowledge.

### ⚙️ Installation

#### Local

At the root og the folder run the following command to download the dependencies:

```bash
go mod download
```

Then, we need to build the binary:

```bash
go build .
```

Finally, we can run the executable:

```bash
./taskit
```

#### Gitpod

You can also use Gitpod to run this project. Gitpod is a free online IDE that allows you to run this project in the cloud. Click the button below to open this project in Gitpod:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Pradumnasaraf/taskit)

### 📝 Usage

We can perform tasks like add, delete, update and list tasks. We can also delete all tasks.

```
Usage:
  taskit [flags]
  taskit [command]

Available Commands:
  add         Add a new task
  delete      Delete a task
  deleteall   Delete all tasks
  done        Mark a task as done
  help        Help about any command
  list        List all tasks
  update      Update a task by ID

Flags:
  -h, --help   help for taskit
```

### 📜 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

### 🛡 Security

If you discover a security vulnerability within this project, please check the [SECURITY](SECURITY.md) for more information.

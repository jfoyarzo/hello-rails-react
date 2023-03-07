# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [📖 Hello Rails-React ](#-hello-rails-react-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [🚀 Live Demo ](#-live-demo-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
    - [Run tests](#run-tests)
    - [Deployment](#deployment)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# 📖 Hello Rails-React <a name="about-project"></a>
**Hello Rails-React** is an exercise created for the Microverse curriculum. It consists of a basic Rails app with a frontend built with React and Redux Toolkit. The root page displays a random greeting from the previously set up database table.

## 🛠 Built With <a name="built-with"></a>
### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://redux-toolkit.js.org/">Redux Toolkit</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://guides.rubyonrails.org/index.html">Ruby on Rails</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Displays a random greeting**, given by the Redux state, on the root path of the app.
- **API endpoint** which selects a random record from the table Greetings and returns it in JSON format
- **Redux Toolkit** state implementation with `createAsyncThunk` which makes a request to the API endpoint and generates a state with the response.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

## 🚀 Live Demo <a name="live-demo"></a>

This is simply an exercise and it will not be deployed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites
To run this project you need:
- Ruby version 2.7.0+
- Rails version 7+
- PostgreSQL
- Node.js
- Npm or Yarn

### Setup

Clone this repository to your desired folder:

```
https://github.com/jfoyarzo/hello-rails-react.git
```

```
cd hello-rails-react
```

### Install

Install this project with:

```
bundle install
```
```
npm install
```
or
```
yarn install
```

### Usage

This app uses PostgreSQL databases for data preservation. Please provide valid credentials in a `.env` file and place it in the root folder.<br><br>
To initialize the database run:<br>
```
rails db:create
```
```
rails db:migrate
```

To run the server, execute the following command:
```
rails s` or `rails server
```
this will start the server on http://localhost:3000/

### Run tests
N/A

### Deployment

N/A

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Felipe Oyarzo**

- GitHub: [@jfoyarzo](https://github.com/jfoyarzo)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/jorge-felipe-oyarzo-contreras)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

This is simply an exercise and future features will not be added.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/jfoyarzo/hello-rails-react/issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project please give it a star ⭐

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>
- Your name will be here if you contribute 😎

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
# Graph Traversal Visualiser 2.0


## Intro
Visualise the path from multiple nodes to another byt using common algorithms like DIJKSTRA, BFS, DFS and A star.
- You can find the live deployment [here](https://pathssearch.netlify.app)

## 🔍 Preview

<img width="1006" alt="Screenshot 2023-09-14 at 1 35 25 PM" src="https://github.com/somtooriaku/PathsSearch/assets/59647845/44bc83c0-4df4-422e-9a6f-84e78944e820">
<img width="1006" alt="Screenshot 2023-09-14 at 1 35 34 PM" src="https://github.com/somtooriaku/PathsSearch/assets/59647845/c7606884-43be-4fe2-b072-3316f5d732a5">

## 📚 Table of Contents

- [🔍 Preview](#-preview)
  - [💻 Desktop](#-desktop)
- [📚 Table of Contents](#-table-of-contents)
- [🚀 Features](#-features)
- [🔧 Getting Started](#-getting-started)
  - [Run Development Environment](#run-development-environment)
  - [Build for Production](#build-for-production)
- [👩‍💻 Technologies and Libraries Used](#-technologies-and-libraries-used)
- [♿ Accessibility](#-accessibility)
- [🧪 Testing](#-testing)
- [📝 Notes](#-notes)



## 🚀 Features

The application visualised the path from one point to another. Can be manually set to:

- Traverse from a starting node to the end ndoe
- Place walls between the points to find alternate paths
- Place traffic between the points which would remove when the node has been met twice.

## 🔧 Getting Started
Clone the project

```bash
  git clone git@github.com:somtooriaku/PathsSearch.git
```

Go to the project directory

```bash
  cd YouTube
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

Remember to install dependencies after cloning it locally.

### Run Development Environment

```bash
yarn dev # npm run dev
```

### Build for Production

```bash
yarn build # npm run build
```


## 👩‍💻 Technologies and Libraries Used

- React
- TypeScript
- Jest

Bootstrapped with my [React.js template](https://github.com/facebook/create-react-app).

## ♿ Accessibility

This application was built using a design first principle and is fully accessible on all possible platforms. The design is restructed for all forms of devices. It also has an accessibility score of 100 according to Google lighthouse. This was achieved using [semantic elements](https://developer.mozilla.org/en-US/docs/Glossary/Semantics) and aria labels using [a11yproject's checklist](https://www.a11yproject.com/checklist/).

## 🧪 Testing

Unit tests have been written for all components using Jest. You can run all tests in watch mode by using the command line:

```bash
yarn test # npm run test
```

Alternatively, generate coverage by using the following:

```bash
yarn test:coverage # npm run test:coverage
```

## 📝 Notes

All components were developed from scratch and implemented based on the design system created for this challenge.




## License

[MIT](https://choosealicense.com/licenses/mit/)



## License

[MIT](https://choosealicense.com/licenses/mit/)


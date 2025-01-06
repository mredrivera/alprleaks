# ALPR Leaks

![CSV file of data collected from script](./docs/csv.png)

Log license plates, vehicle make, vehicle color, and vehicle model to a CSV along with a JPEG image of the vehicle from Motorola ALPRs exposed to the public internet.

This script is preloaded with 3 IP addresses, but more can be added.

Research credit to [Matt Brown](https://www.youtube.com/@mattbrwn). For more into, watch his [YouTube video](https://youtu.be/0dUnY1641WM?si=A2geeOF-FCunDW-v) reporting this vulnerability.

## Running Locally

To run this project locally, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (version 6 or higher)

### Installation

1. Clone the repository:
  ```sh
  git clone https://github.com/frillweeman/alprleaks.git
  ```
2. Navigate to the project directory:
  ```sh
  cd alprleaks
  ```
3. Install the dependencies:
  ```sh
  npm install
  ```

### Running the Project

1. Compile the TypeScript files:
  ```sh
  npm run build
  ```
2. Start the application:
  ```sh
  npm start
  ```

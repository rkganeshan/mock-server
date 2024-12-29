Steps to run this project locally.
Assumption: Node 16 or higher is a pre-requisite. Visit https://nodejs.org/en to get the package.

1. Clone the repository:

   ```bash
   git clone https://github.com/rkganeshan/soar-mock-serve.git
   cd soar-mock-server
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   or if using Yarn:

   ```bash
   yarn install
   ```

## Environment Variables

Add your environment variables in a `.env` file at the root of the project. Example:

```env
PORT=8080
```

## Usage

If you point to local you need to run the json-server which is a mock server locally.
To run this

To run the server locally:
npm run dev

You can view them here:
Resources
http://localhost:8080/user
http://localhost:8080/dashboard

Home
http://localhost:8080

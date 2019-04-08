# Voting System Truffle Box

## Installation

1. Install Truffle globally.
    ```javascript
    npm install -g truffle
    ```

2. Download the box. This also takes care of installing the necessary dependencies.
    ```javascript
    truffle unbox pet-shop
    ```

3. Run the development console.
    ```javascript
    truffle develop
    ```

4. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

5. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```
    
    
    Steps:
    
    1) Enter UID number to login. (Default 1111111111 or 2222222222)
    2) Select candidate of choice and vote.
    3) Goto url http://localhost:3000/results.html to view results.

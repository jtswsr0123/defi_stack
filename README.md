example of defi platform for user to take token, year yields, issue token, and unstake. 

run:
brownie run .\scripts\deploy.py --network rinkeby
brownie run .\scripts\deploy.py --network kovan
brownie run .\scripts\deploy.py 

for front_end setup:
1. install yarn, npx
2. "npx create-react-app front_end –template typescript" to create a react app
3. "npm install @usedapp/core" get the usedapp tools
4. add various packages: "yarn add ethers", "yarn add @material-ui/lab", "yarn add @ethersproject/units"


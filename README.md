# Foundry Cheatsheet for quick reference
## Forge
1. Compile Contract
```shell
forge compile
# or
forge build
```

2. Testing
```shell
forge test <pathname>

Options:
--match-path #or --mp // To test specific file
--match-test #or --mt // To test specific function
--fork-url // To fork chain
-v #or v(s) for test result Verbosity 
```

3. Coverage
```shell
forge coverage --fork-url <RPC_URL>
```
Example:
![Screenshot 2024-05-08 at 1 01 00 PM](https://github.com/honghan-dev/foundry-cheatsheet/assets/52853446/3856390e-6849-4d60-ad94-e2234aa9e071)

## Cast

## Anvil

yarn set version berry
yarn create react-app react-base --template typescript


## yarn workspace cli
1. workspace 스크립트 실행: yarn workspace <WORKSPACE_NAME> <COMMAND_NAME>
2. workspace 의존성 추가: yarn workspace client add <PACKAGE_NAME>
3. workspace 의존 관계 확인: yarn workspaces info
4. root 의존성 추가: yarn add <PACKAGE_NAME> -W

## vscode extension
1. Install ZipFs - a zip file system
2. Select TypeScript: Select TypeScript Version...
3. Select Use Workspace Version
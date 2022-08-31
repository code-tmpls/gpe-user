# gpe-user

1) Authenticate yourself using PAT
 npm login --scope=@OWNER --registry=https://npm.pkg.github.com

> Username: USERNAME
> Password: TOKEN
> Email: PUBLIC-EMAIL-ADDRESS

2) Create .npmrc File as follows:
@OWNER1:registry=https://npm.pkg.github.com/
@OWNER2:registry=https://npm.pkg.github.com/

OWNER1 = Name or Organization based on the package exists.
OWNER2 = Name or Organization based on the package exists.

3) Then, install the package
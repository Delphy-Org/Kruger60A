# Delphy: Helping developers choose the right package for their project

![hero image](https://ik.imagekit.io/delphy/yes_gJudYscdn.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1650046214039)

Choosing the right package for a project is no easy job. Developers sometimes spent hours researching packages to find simple details like whether the package is maintained or not, the number of open issues, the popularity of the package, the size of the package, etc.

In this blog, we'll introduce a service called Delphy. Delphy takes this challenge of researching packages and aims to simplify it so developers don't need to spend hours.

But before we start talking about Delphy, let's understand how to choose a package in general for a project.

## Selecting a package
As mentioned earlier, researching a package sometimes take hours and there are several steps in it. Below, I'm detailing the steps in detail.

### Popularity
One of the first steps in researching packages is to check the popularity of the package on GitHub. A high number of GitHub stars and forks usually means a lot of people find the package useful. A high number of package downloads also means that the package is useful. 

### Open and closed Issues/PRs
Whenever we install a package, the last thing that we want is bugs. To find whether there are bugs present in the package or not, check the number of open issues, PRs, and closed issues, PRs.

Usually a lot of open issues, PRs mean there are several open bugs present in the package. Always avoid libraries with huge open of open issues and PRs.

### Contributors
When a project, a huge number of contributors contribute to the project, it usually means the package is stable and actively maintained. Always try to use packages when there are multiple contributors in the package.

### Maintanance
Frequently maintained packages are always a green flag. It usually means the package is stable, there is less number of bugs. Also, it is an indication that future issues will be resolved.

### Size
The size of a package is another important metric that we need to consider. Usually, packages of huge sizes can make the application slow. 

Furthermore, in front-end applications, packages with huge sizes should be avoided as it might increase the bundle size.

### Vulnerabilities
In recent days, open-source packages are a huge target for hackers. In several cases, hackers hijack a package and inject malicious code. So checking the number of known vulnerabilities is super important.

### Package License
Another important metric that is needed to check is the license of the package. Licenses like MIT and Apache provided minimal restrictions whereas licenses like GPL and LGPL are more restrictive.

## Introducing Delphy
As discussed above, there are several steps in researching a package. To do this research developers may need to visit several websites, and developers may need to spent hours researching.

Delphy try to solve this problem of researching packages by aggregating data from various platforms. That means instead of visiting several websites, developers can get all the information in one place.

### What data it provides
Delphy collects data from several platforms like NPM, PyPI, GitHub, BigTable, etc. 
  - Badges
  - Reviews
- Future Roadmap
- Links
- Conclusion
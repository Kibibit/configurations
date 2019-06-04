# configurations


<p align="center">
  <a href="https://github/apps/l1ntit" target="blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Font_Awesome_5_solid_sliders-h.svg/512px-Font_Awesome_5_solid_sliders-h.svg.png" width="150" alt="kibibit Logo" />
  </a>
  <h2 align="center">@kibibit/configurations</h2>
</p>
<p align="center">
  Global configurations for kibibit projects
</p>
<hr>

## How to use

You can copy the files directly to a project based on each configuration's own readme.

The BETTER way to do this is to use **git submodules**. This will allow you to keep configurations up-to-date as they change in this repository.

### git submodule

initialize by going into your project and running
```bash
# add submodule and define the master branch as the one you want to track
cd <your_project>
git submodule add -b master https://github.com/Kibibit/configurations.git
git submodule init 
```

to update to the latest files, run this:
```bash
# update your submodule --remote fetches new commits in the submodules
# and updates the working tree to the commit described by the branch
git submodule update --remote
```

## Dependencies:

- `.eslintrc`: [`eslint`](https://www.npmjs.com/package/eslint), [`ESLint-Plugin-Lodash`](https://www.npmjs.com/package/eslint-plugin-lodash)
- `.tslint`: TBD

###### john adams web management with ==markdown==

---

A simple git rule says: <br>
After I pull a project out of gitHub, the first thing to do is to rename its remote which is **origin**. How do I rename and what's the new name going to be?

- [x] git remote rename origin upstream
- [ ] ~~git add remote origin upperstream~~
- [ ] ~~git super remane main origin~~

#### Here are a coupls of git commands

| syntax                                                             | meaning                                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| git init                                                           | initializes directory-connection with gitHub                                   |
| git add _(+fileName)_                                              | add a specific workprogress to git                                             |
| git add .                                                          | adds all progress in directory to git                                          |
| git commit -m                                                      | add a message of what you've done so far                                       |
| git branch                                                         | In which branch am I ?                                                         |
| git branch -M main _(special case, only once)_                     | rename Master _(-M)_ into **main**                                             |
| git branch _super_                                                 | make a new branch, name it _super_                                             |
| git checkout _super_                                               | move to branch named _super_                                                   |
| git checkout -b _super_                                            | make a new branch, name it _super_, then move to _super_                       |
| ` git remote add origin git@github.com:johnxadams/projectName.git` | builds a bridge named **origin** from local _(user-pc)_ to cloud _(gitHub)_    |
| git remote remove origin                                           | remove origin                                                                  |
| git push -u origin main (special case, only once)                  | making sure the bridge is between main(local) and main(cloud), -u means update |

---

<style>
   p
 {
  font-size: 1rem;
  margin-bottom: 1.3rem;
  color: darkred
}
    </style>

_<p> Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. </p>_

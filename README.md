# str-csapat-teszt
Kizárólag a Github tesztelésére

## A Struktúraváltó csapat github-os együttműködés tesztelésére.

### Branch készítése:
- Githubon belépve abba a branch-be, melyből az újat ki akarom ágaztatni, majd a Branch nevét tartalmazó gombra kattintva
  - a megnyíló ablak input mezőjébe beírva az új branch nevét és Enter-t nyomva létrejön a megadott nevű új branch;

  ![Create-new-branch-1](./img/create-new-branch-1.jpg)
  
  ![Create-new-branch-2](./img/create-new-branch-2.jpg)

  - s a létrehozást követően a github át is áll az új branch-re.
  
  ![change-to-new-branch](./img/gh-sets-itself-to-the%20new-branch.jpg)



### Közreműködő meghívása:
- A **main** branch-ből a repository neve alatti menüsorban a **Settings** fülre kattintva;
- majd a megnyíló oldalon a **Manage access**-t választva

![Manage access](./img/invite-sb-to-work-together-with-me-in-my-repo-1.jpg)

- adható hozzá a meghívni kívánt Github fiók tulajdonosa
![Select somebody](./img/invite-a-collaborator-1.jpg)

- meghívó elküldése
![Send invite to the selected collaborator](./img/send-invite-to-a-collaborator.jpg)



### Váltás új branch-re:
- A VSC bal alsó sarkában a branch gombon kattintva
![co-to-new-branch-1](./img/checkout-to-new-branch-in-vsc-1.jpg)

- a felugró ablakban kiválasztható, hogy melyik létező branch-re akarunk váltani, vagy akár újat is létrehozhatunk
![co-2-new-br-2](./img/checkout-to-new-branch-in-vsc-2.jpg)

- váltást követően a bal alsó sarokban ellenőrizzük, hogy a megfelelő branch-ben vagyunk-e
![in-new-br](./img/in-the-new-branch.jpg)



### Elkészült fejlesztés elágazásból felsőbb branch-be beolvasztásának kérése (Pull request létrehozása)
- Új Pull request indítása
![add-new-pq](./img/add-new-pull-request.jpg)

- feladóként beállítom, hogy honnan, hová akarom továbbadni a munkámat
![from-where-to-where](./img/from-where-to-where.jpg)

- rövid leírás, hogy mit is szeretnék benyújtani, majd kattintás a 'Create pull request' gombra
![what-to-add](./img/what-i-want-to-add.jpg)



### Elkészült fejlesztés beolvasztása felsőbb branch-be (Merge pull request)
- A benyújtott pull request
![new-submitted-pq](./img/new-prq-waiting-for-merge.jpg)

- elfogadjuk vagy kommenteljük?
![merge-or-comment](./img/merge-or-write-comment.jpg)

- elfogadás/merge
![merge](./img/merge-pq-1.jpg)

- beolvasztva
![merged](./img/merged-pq.jpg)

:)
### Mappacks

Mappacks are one of the few things that can be created easily using the tools page however this page doesn't give you full control over the mappacks

![Mappack-tools-page](https://raw.githubusercontent.com/Wyliemaster/fh-faq/main/images/mappacks/tool.PNG)

To fully customise mappacks, you will need to log into phpmyadmin and go to the mappack table

![mappack-table](https://raw.githubusercontent.com/Wyliemaster/fh-faq/main/images/mappacks/database01.PNG)

Once you enter the mappack table a list of created mappacks will be shown.

![list-of-packs](https://raw.githubusercontent.com/Wyliemaster/fh-faq/main/images/mappacks/database02.PNG)

There are **2** ways you can proceed

- Edit existing MapPacks

- Inserting new MapPacks

To insert a new a new mappack you just need to click the `Insert` button at the top of the window and then you fill in the following information

![insert](https://raw.githubusercontent.com/Wyliemaster/fh-faq/main/images/mappacks/insert.PNG)

Editing existing packs is quite similar however you click on the edit button that is prefixed to the start of the pack

![edit](https://raw.githubusercontent.com/Wyliemaster/fh-faq/main/images/mappacks/edit.PNG)

After doing this, you will be presented with a similar screen

![data](https://raw.githubusercontent.com/Wyliemaster/fh-faq/main/images/mappacks/data.PNG)

Below is a table explaining what each component represents

| Column | value |
|:-------|:------|
| ID | The mappackID |
| name | The name of the mappack |
| levels| An array of levels in the mappack - you can add as many levels as you want as long as you seperate each level with a `,` |
| stars | the number of Stars rewarded for completing the pack  |
| coins | The number of Secret Coins rewarded for completing the pack |
| difficulty | The ID for the difficulty face - a table showing the ID's can be found below |
| rgbcolors | The colour of the mappack text - the colour is an [RGB Value](https://g.co/kgs/UZ5shP) |
| colors2 | The colour of the mappack bar - the colour is an [RGB Value](https://g.co/kgs/UZ5shP) |

### **Difficulty Table**

| Value | Difficulty |
|:------|:-----------|
| 0 |  auto | 
| 1 |  easy | 
| 2 |  normal | 
| 3 |  hard | 
| 4 |  harder | 
| 5 |  insane | 
| 6 |  hard demon | 
| 7 |  easy demon | 
| 8 |  medium demon | 
| 9 |  insane demon | 
| 10 |  extreme demon |
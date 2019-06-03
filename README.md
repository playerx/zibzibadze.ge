# Family Tree
Idea by: Alexander Zibzibadze

Implemented by: Ezeki Zibzibadze


## Commits
Used [Angular Commit Message Guideline](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit), plus one additional type `data:` for `data.json` changes

## Data Structure
sample:
```js
{
    // Unique Id
    "id": 10,

    // Parent Id
    "parentId": 4,

    // OPTIONAL, parent relation number (if there are multiple ones)
    "parentRelId": 2,

    // Personal Info
    "name": "Name Surename",

    // OPTIONAL
    "imageUrl": "./images/people/[name]-[surename].jpg",

    // OPTIONAL, toptal profile url
    "toptalUrl": "",

    // OPTIONAL, facebook profile url
    "facebookUrl": "",

    // OPTIONAL, Relations
    "rels": [
        {
            "name": "Name Surename",
            "imageUrl": ""
        }
    ]
},
```

## Supported social links
* Toptal - `toptalUrl`
* Facebook - `facebookUrl`


## Limitations
* Currently there is one limitation, man (or woman) can have registered max 4 relations :)
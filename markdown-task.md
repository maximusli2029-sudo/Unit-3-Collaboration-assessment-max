Welcome to **TreeLife**, your guide to learning about the beauty, diversity, and importance of trees around the world.

---
### About Us
At **TreeLife**, we're passionate about forests and green living.

Our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry. 
- Encourage reforestation projects.

>"The best time to plant a tree was 20 years ago. The second best time is now." 
>—Chinese Proverb

---
### Featured Trees

#### Oak Tree

**Scientific Name:** *Quercus robur*

Known for its strength and longevity, the oak is a symbol of endurance.

<img src="https://sites.dartmouth.edu/dujs/files/2020/11/EL-1.png" alt="Quercus dominantur: How botanists uncovered the story of the oak tree&#39;s  success – Dartmouth Undergraduate Journal of Science"/>

---
#### Pine Tree

**Scientific Name:** *Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.

<img src="https://dfjx2uxqg3cgi.cloudfront.net/img/photo/52294/52294_00_2x.jpg?20151124093612" alt="Beautiful Pine Trees On Mountain Photo (52294) - YouWorkForThem"/>

---
### Tree Identification Tool
You can use this simple **Javascript** function to identify a tree by its characteristics:

```
function identify_tree(leaf_shape, region){
    if (leaf_shape == "needle" && region == "cold") {
        return "Pine Tree"
    } else if(leaf_shape == "broad" && region == "temperature") {
        return "Oak Tree"
    } else {
        return "Unknown Tree" 
    }
}
console.log(identify_tree("needle", "cold"))
```
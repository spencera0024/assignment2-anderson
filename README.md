# assignment2-anderson
# Spencer Anderson
### Favorite Sport: American Football
I enjoy football because the game is almost always close. There **never** seems to be a dull moment in the game. There also aren't that many games in a season, making each one feel super **special**. 
***
# Favorite team and players
### Kansas City Chiefs 
1. Patrick Mahomes 
2. Travis Kelce 
3. Chris Jones 

Other teams that may be fun to watch: 
* New York Giants 
* New York Jets 
* New Orleans Saints

[Link to my About Me page.](https://github.com/spencera0024/assignment2-anderson/blob/main/AboutMe.md)

# Countries you should visit 
###
| Name | Why visit? | Number of days recommended | 
| --- | --- | ---: |
| United Kingdom | It has a very large amount of sights to see. | 7 days | 
| Spain | Beautiful country with many places to see. | 5 days | 
| Italy | Beautiful buildings with historic artworks. | 5 days | 
| Egypt | The pyramdids alone making it worth visiting. | 2 days |

***
# Funny Quotes
###
> Clothes make the man. Naked people have little or no influence in society. - *Mark Twain*

> Before you marry a person, you should first make them use a computer with slow Internet to see who they really are. - *Will Ferrell*

***
# Code Snippets
###
> I think a better approach for this would be to create a single nested (hierarchical) custom post type.
For example, it can be series.
Then a single series named sample-series as a top level post of series post type: site.com/series/sample-series/.
Then seasons named season-one, season-two etc. can be children of sample-series, like: site.com/series/sample-series/season-one, site.com/series/sample-series/season-two.
Similarly, episodes can be children of those seasons, like: site.com/series/sample-series/season-one/episode-one, site.com/series/sample-series/season-one/episode-two etc.
Same thing can be done by default by WordPress page, since pages are by default hierarchical.

```
<h3>All Post Meta</h3>

<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>
```



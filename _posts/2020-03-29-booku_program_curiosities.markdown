---
layout: post
title:      "Booku program curiosities"
date:       2020-03-30 03:44:33 +0000
permalink:  booku_program_curiosities
---

For my booku program, I made a small animation of sorts. Though this is quite basic code, it delighted me. 

My program is a CLI utilizing an API. It presents users with a selection of ten books on a bookshelf and asks them to choose a book, based on index, for more details. Upon choosing a book and being presented with author, description, and other details, the screen slowly inches up by two times the row of code I have below.  At this point in the program, if anything from 4-10 is selected by the user, 14 rows of the below code will be presented one row at a time, with text between some rows announcing that a secret passageway behind the bookshelf has been discovered. 

```
module RepeatRepeat

    require 'colorize'

    def curtains(n, a)
        while n > 0
          puts "      o          o          o          o          o          o          o        ".colorize(:color => :blue)
          puts "   o     o    o     o    o     o    o     o    o     o    o     o    o     o     ".colorize(:color => :blue)
          puts "o          o          o          o          o          o          o          o   ".colorize(:color => :blue)
           n -= 1
          sleep(a)
        end
    end

end
```

Again, though this is simple code, it excited me to see my program come to life. Onward and upward. 

: )

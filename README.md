# Fuzz-Buzz-exercise-
On occasion you meet a developer who seems like a solid programmer. They know their theory, they know their language. They can have a reasonable conversation about programming. But once it comes down to actually producing code they just don’t seem to be able to do it well.  You would probably think they’re a good developer if you’ld never seen them code. This is why you have to ask people to write code for you if you really want to see how good they are. It doesn’t matter if their CV looks great or they talk a great talk. If they can’t write code well you probably don’t want them on your team.  After a fair bit of trial and error I’ve come to discover that people who struggle to code don’t just struggle on big problems, or even smallish problems (i.e. write a implementation of a linked list). They struggle with tiny problems.  So I set out to develop questions that can identify this kind of developer and came up with a class of questions I call “FuzzBuzz Questions” named after a game children often play (or are made to play) in schools in the UK.  In this game a group of children sit around in a group and say each number in sequence, except if the number is a multiple of three (in which case they say “Fuzz”) or five (when they say “Buzz”). If a number is a multiple of both three and five they have to say “Fuzz-Buzz”.
git remote add origin https://github.com/markkinuthia/Fuzz-Buzz-exercise-.git
git push -u origin master
    

Fuzz Buzz Exercise


R Markdown
i <- 1
d <- NULL
while(i < 100){
  {
  {
    ifelse(i %% 5 ==0 & i %% 3 == 0,x<-"Fuzz-Buzz",
         ifelse(i %% 5 == 0, x<-"Buzz",
                ifelse(i %% 3 == 0,x<-"Fuzz",x <- print(i))))
    }
  d <- rbind(d,data.frame(x))
    }
  i<-i+1
}
## [1] 1
## [1] 2
## [1] 4
## [1] 7
## [1] 8
## [1] 11
## [1] 13
## [1] 14
## [1] 16
## [1] 17
## [1] 19
## [1] 22
## [1] 23
## [1] 26
## [1] 28
## [1] 29
## [1] 31
## [1] 32
## [1] 34
## [1] 37
## [1] 38
## [1] 41
## [1] 43
## [1] 44
## [1] 46
## [1] 47
## [1] 49
## [1] 52
## [1] 53
## [1] 56
## [1] 58
## [1] 59
## [1] 61
## [1] 62
## [1] 64
## [1] 67
## [1] 68
## [1] 71
## [1] 73
## [1] 74
## [1] 76
## [1] 77
## [1] 79
## [1] 82
## [1] 83
## [1] 86
## [1] 88
## [1] 89
## [1] 91
## [1] 92
## [1] 94
## [1] 97
## [1] 98
d
##            x
## 1          1
## 2          2
## 3       Fuzz
## 4          4
## 5       Buzz
## 6       Fuzz
## 7          7
## 8          8
## 9       Fuzz
## 10      Buzz
## 11        11
## 12      Fuzz
## 13        13
## 14        14
## 15 Fuzz-Buzz
## 16        16
## 17        17
## 18      Fuzz
## 19        19
## 20      Buzz
## 21      Fuzz
## 22        22
## 23        23
## 24      Fuzz
## 25      Buzz
## 26        26
## 27      Fuzz
## 28        28
## 29        29
## 30 Fuzz-Buzz
## 31        31
## 32        32
## 33      Fuzz
## 34        34
## 35      Buzz
## 36      Fuzz
## 37        37
## 38        38
## 39      Fuzz
## 40      Buzz
## 41        41
## 42      Fuzz
## 43        43
## 44        44
## 45 Fuzz-Buzz
## 46        46
## 47        47
## 48      Fuzz
## 49        49
## 50      Buzz
## 51      Fuzz
## 52        52
## 53        53
## 54      Fuzz
## 55      Buzz
## 56        56
## 57      Fuzz
## 58        58
## 59        59
## 60 Fuzz-Buzz
## 61        61
## 62        62
## 63      Fuzz
## 64        64
## 65      Buzz
## 66      Fuzz
## 67        67
## 68        68
## 69      Fuzz
## 70      Buzz
## 71        71
## 72      Fuzz
## 73        73
## 74        74
## 75 Fuzz-Buzz
## 76        76
## 77        77
## 78      Fuzz
## 79        79
## 80      Buzz
## 81      Fuzz
## 82        82
## 83        83
## 84      Fuzz
## 85      Buzz
## 86        86
## 87      Fuzz
## 88        88
## 89        89
## 90 Fuzz-Buzz
## 91        91
## 92        92
## 93      Fuzz
## 94        94
## 95      Buzz
## 96      Fuzz
## 97        97
## 98        98
## 99      Fuzz
   

for (month_name in month.abb[1:4])
{ print(paste("This month", month_name, "beautiful!!!"))}

 for (month_name in month.abb[1:4])
+   { print(paste("This month", month_name, "beautiful!!!"))}
[1] "This month Jan beautiful!!!"
[1] "This month Feb beautiful!!!"
[1] "This month Mar beautiful!!!"
[1] "This month Apr beautiful!!!"

oddnumbers <- seq(1,100,2)
> odd_numbers <- seq(1,100,2)
> for(number in odd_numbers){
+   if(number %% 3 ==0){
+     print(number)
+   }
+ }
[1] 3
[1] 9
[1] 15
[1] 21
[1] 27
[1] 33
[1] 39
[1] 45
[1] 51
[1] 57
[1] 63
[1] 69
[1] 75
[1] 81
[1] 87
[1] 93
[1] 99
print('happy birthday')
[1] "happy birthday"
name <-('mariya','jayamma','virat')
print('happy birthday')
for(dancers in names ){
  text <-paste("happy birthday......")
}
print(paste("This month", month_name, "beautiful!!!"))
[1] "This month Apr beautiful!!!"
>   for(players in names){
+     text <- paste("Happy New Year",players)
+     print(text)
+   }
[1] "Happy New Year IND"
[1] "Happy New Year GBP"
[1] "Happy New Year USD"
[1] "Happy New Year AED"



>   for(months in names) {
+     text <- paste(months, "IS BEAUTIFUL")
+     print(text)
+   }
[1] "IND IS BEAUTIFUL"
[1] "GBP IS BEAUTIFUL"
[1] "USD IS BEAUTIFUL"
[1] "AED IS BEAUTIFUL"



>   for (players in name) {
+     text <- paste("HAppy New Year", players)
+     print (text)
+   }  
for(players in names){
+     if(players == 'Ganguly' || players == 'Gayle'){
+       text <- paste("Happy New Year Dada!")
+     } else { text <- paste("Happy New Year",players)}
+     
+     print(text)
+     
+   }  
[1] "Happy New Year IND"
[1] "Happy New Year GBP"
[1] "Happy New Year USD"
[1] "Happy New Year AED"


iris$Species %in% "virginica"  
  [1] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [14] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [27] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [40] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [53] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [66] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [79] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [92] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE  TRUE  TRUE  TRUE  TRUE
[105]  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE
[118]  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE
[131]  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE
[144]  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE  TRUE


month.abb %in% c('jan','apr','dec')
 [1] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE


df$is_setosa <- ifelse(df$Species=='setosa',
+                         TRUE,
+                         FALSE)

>  df$is_setosa <- ifelse (df$Species=='setosa',
+                         TRUE,
+                         FALSE)

 df <- iris
 
 df$is_setosa <- ifelse (df$Species=='setosa',
                        TRUE,
                        FALSE)
 View(mtcars)
 
 df <-mtcars
 
 three_gears - "yes"/"no"
 
 df2=mtcars
 
 df2$Three_gears= ifelse(df2$gear ==3,"Yes","No")
 
 df2

# Entry 3
##### 2/12/23

## Content

As I continue building my app on Xcode using SwiftUI, I improvise on my ideas and plan. While I was thinking about my plan for my app, I realized that if I was to create a college organizer app, I would have to store users' data so that they could all log in to keep track of their information. I then realized that I could create a college Advisor app that will contain different types of advice on how to successfully start and finish the college application process. As I am creating my app, I am constantly thinking of how I want my app to look and function as it will be important for the preciseness of the app. 

I am learning about the different types of methods and functionalities that I could use within Xcode. I found out that I can change the icon for my app and add pictures to my app by designing my own and implementing it inside the `Assets` folder on my terminal. I also found out that `Vstack` allows to stack views vertically. I learned a lot through this [tutorial](https://www.youtube.com/watch?v=EJQW864XpmA&t=1526s) I found for beginners that allowed me to complete my break goal. 

One conflict I encountered, was that I assigned a variable to something, however, I couldn't change it later on. I later learned if you are going to change something that's assigned to a variable later on, you will need to use `@State Var` which allows the variable that is being assigned to something to be changed.

```Java
struct ContentView: View {
    var body: some View {
        Color.green
            .ignoresSafeArea()
            .overlay(
        VStack {
        Text("College Application Advice!")
                .padding(40)
    
        Image("colleges-pic")
        .imageScale(.small)
        .foregroundColor(.blue)
            
            Button("Continue") {
               secondPage()
            }
        }) 
    }
}
```
## Engineering Design Process:

Currently where I am in the [Engineering Design Process](https://hstatsep.github.io/students/#edp) is that I am creating my prototype but also improvising as well along the way. As I am building my app, I am changing my original ideas to new ideas that I believe will be best for me, as well as improvising my app on how things should look and function. My next steps would be to test my prototype as well as to continue improvising and asking for help when needed. 

## Skills:

The [`skills`](https://hstatsep.github.io/students/#skills) I have gained throughout my learning process that I am learning to have a growth mindset and become more creative. Many times as I am trying to figure things out, I feel like giving up, especially when a certain code doesn't want to work or when I can't figure a certain thing out. I have learned to be patient and to learn from my process. I also learned to be more creative because as I mentioned previously, as I am creating my app, I am changing the app throughout based on what I feel would be best which opens my creativity to a new level. 


[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)



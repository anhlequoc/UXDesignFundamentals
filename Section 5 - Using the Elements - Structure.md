## Using the Elements - Structure 

### Defining Structure:
- Structure defines how users **get to a given screen** and **where they can go** when they're done
- Structure also defines **categories of information** contained within the app or website, or system 
- Structure is created by **interaction design**, which presents information in a way people can interact with it
- Structure is also created by **information architecture** - organization, labeling, search and navigation systems
- Good structure organizes information in a way that provides **intuitive** access to content (**intuitive** means **Single Trial Learning** - user does it one time and remember forever)

- Structure should be **appropriate**
    + Với site (app, system) simple (chứa basic content, như là training sites): structure là theo hướng linear narrative (predictable structure)
    + Với site (app, system) phức tạp vừa: structure có thể phức tạp hơn
    + Với site (app, system) phức tạp (dành cho user có kinh nghiệm, có đào tạo): cấu trúc site phức tạp (non-linear/hyperlinked), cấu trúc flexible, nhưng có thể confusing
    
    Ảnh minh họa: ![Ảnh minh họa](http://i.imgur.com/Ctefskq.png)

- Structure should be **flexible**: should accommodate future **change**

### Interaction Design (IXD)
>Interaction design defines the **structure** and **behavior** of interactive systems:
> + It creates **meaningful relationships** bewteen people and the things they use
> + It effectively communicates **interactivity** and **functionality**
> + It reveals simple and complex **workflows**
> + It inform users about **state changes**
> + When done right, it prevents user **error**

1) Good interaction design should include 5 things: **consistent, predictable, learnable, visiable, provide feedback**

2) IXD is **consistent**: don't be different just to be different; be different when it makes something better
- Components with similar **behavior** should have a **similar appearance**: ví dụ các message thông báo thành công, cảnh báo, lỗi ... phải có cùng cách thức xuất hiện
- Trong hầu hết các trường hợp thì consistency được thể hiện trong 2 hướng chính:
    + Behavior:
        transitions, rollover, tooltips... should behave consistently
        Leverage the visitor's prior experience (here and elsewhere)

    + Voice:
        **Labels** and **terms** should be the same throughout the experience
        **Content** and **imagery** should have a stable, consistent style
    
- Design pattern: should use the same style of design pattern
    + Reusable solutions to **recurring** problems
    + Content may change, but **interaction** and **process** stay the same
    + Makes **actions** and **results** consistent (and predictable)

3) IXD is **visible**
- **Discoverability**: shouldn't involve luck or chance
- People should able to tell that an **opportunity to interact** is available
- Use **content hinting** - avoid "false bottoms" when more content and interactivity exists below the visible space
- **click and tap**:
    + People will attempt to interact with **anything** that might possibly be clickable
    + **Standard UI components: are understood to be interactive - use them!
    + Diffrent text color, 3D and icons all **invite** interaction
- **touch and gesture** (màn hình cảm ứng) (gesture can be **arbitrary**)
    + There is no **hover state** for touchscreens
    + Consider the lefties of the world by making interface **reversible**
    + Don't make people reach over the interface and **obstruct** their view!
- IXD shopuld be easy to **learn** and easy to **remember** (use **once**, learn it **rapidly**, remember it **forever**) (ví dụ: so sán màn hình app của iOS, android, windows phone)

4) IXD is **predictable**
- Can users answer the following questions?
    + Where am I?
    + How did I get here?
    + What can I do here?
    + Where can I go from here?
-> If answer is Yes, you've provided a strong **sense of place**. You've set the correct **expectations** -> You'vemade it possible for people to accrately **predic** the outcomes of their interactions

- Some ways:
    + Show what can be d one while the interface loads
    + Show a high-level view of the **structure** to provide **context** (much like a map)
    + Labels, instruction, icons, and images set **expectations** about:
        What to do (touch here)
        what will happen (open this, drag this over there)
        Where the user will go (foster a sense of place)
        How the screen will **respond** (do X and Y will happen)
    Ảnh: ![](http://i.imgur.com/xMtcfgn.png)

5) IXD provides **feedback**
- Feedback answers for some questions:
    + Location: Where am I?
    + Status: what's happening?
    + Future State: what will happen?
    + Outcomes/Results: here's what happened

- Error prevention is the best error handling - complement, don't complicate. Error messages should:
    + Describe what happened
    + Explain why it happened
    + Suggest a fix
    + never blame the user
    Ví dụ: ![](http://i.imgur.com/ECwp4iQ.png)

6) These 5 principles are **interrelated**:
    **Consistency** heps people use what they know -> **Visibility** of opportunity can invite interaction -> **Learning** is easier when **predictions** are accurate -> **Feedback** facilliates learning

7) Your IXD **marching orders**:
- Remember: you're not designing for **yourself**
- Understand the **goals and needs** you're designing for
- Think hard about the design and the **experience**
- Set the user's expectations for the experience
- Don't hinder, obstruct, or interfere with the experience
- Try to break what you build - be your own worst visitor
**-> Again: you are not designing for yourself**

### Information Architecture
> Information Architecture (IA) is organization and navigation of content:
> - how much of information?
> - order of imporatance and priority?
> -> it's about organizing, categorizing, prioritizing

####Some I.A Pattern:
1) Hierarchical tree: standard site structure, used by most sites. problem: with people who is using small screen because can not see content in depth

2) Hub and Spoke:
![I.A Pattern - Hub and Spokeimage](https://i.imgur.com/zNezfx6.png)

- not good for multi tasking user

3) Nested List:
![I.A - Nested List](https://i.imgur.com/IyktZhl.png)

4) Bento Box (Dashboard):
![I.A Pattern - Bento box](https://i.imgur.com/jvDq5US.png)

- Good for multi-funcitonal tools and content-based tablet apps that have a **similar theme**

5) Filtered view (see a lot on ecommerce sites):
![I.A Pattern - Filtered View](https://i.imgur.com/R0piBuS.png)

- good for user has a high volumn of content
- hard to display on mobile screen

### Organizing Principles
![Organizing Principles - Nodes](https://i.imgur.com/hMkyy6n.png)

Example:
![Example](https://i.imgur.com/V9bVwq4.png)

-> Cần xem objective của từng site/application là gì, information needs là gì?

#### Organizing rules of thumb:
- The organizing principles used at the highest levels of the site or app should be those most closely tied to user needs and business objectives. 
- Those used at lower levels are usually influenced by feature specs and content requirements. 
- Every collection of information has a built-in conceptual structure — and in most cases it has more than one. 
- The hard part isn't creating a structure — it's creating the right structure for our objectives and our users' needs. 

#### organizing with facets 
Facets are attributes of an information set that provide a flexible set of organizing principles for nearly any kind of content. However: 
- Using the wrong facets can actually be worse than using none at all. 
- When users have too many options to sort through, they often can't find anything. 
- It's our job — not the user's — to identify the specific attributes of the information that will be most useful, usable and valuable to our users.


### Roles and Processes
Some examples:
Visual Vocabulary:
![Diagram](https://i.imgur.com/s9gpMR6.png)
![Diagram 2](https://i.imgur.com/rXkb7Q2.png)

### Structures Takeaways: Things to Remember
- Good structure organizes information in a way that provides intuitive access to content. 
- Structure is created by interaction design, which means presenting information in a way people can 
understand or interact with it. 
- Structure is also created by information architecture, which is the combination of organization, labeling, search and navigation systems within any digital product.
- Structure should be appropriate for the audience and flexible to accommodate change. Whether you have a specialist to address structure or not isn't important — but someone needs to do this work! 
- Focus on relationships between content elements:
    + Which categories go together?
    + Which don't?
    + How do the steps in an interaction sequence fit together?


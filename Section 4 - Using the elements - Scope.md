## Using the elements - Scope

### Defining Scope: avoiding perpetual beta
**Reasons to define scope:**
1. Know what you're building:
    - Defining scope forces all players to address **potential conflicts** - before time is invested in designing or building
    - Documenting scope provides a **reference point** for work to be done - and a common way to **describe** that work
    - LEAN/Agiles discourages **lengthy documentation** - but the result is often a product with a slew of features in various stages of completeness
    - Documentation doesn't have to be epic - but a **common understanding** of features, schedules and milestones puts the end squarely in sight
    - A clear description of what you're going to build tells everyone involved what the project's goals are (and when they'll be reached).
    > With no documented requirements, you're playing "telephone": peas -> bees -> knees -> cheese -> fleas

2. Know what you're not building:
**Features** and functionality should align with **strategy**
    - New features often sound like good ideas, but may not suport the **strategic objectives** of the project
    - Ideas for new features almost always emerge **after** a project is underway
    - Clearly identified requirements provide a framework for determining how (or if) additional ideas fit into **what you've already committed to build**

3. Know what you're not building right **NOW**
Identify **what's doable now**, and what has to wait

4. Symptons (dấu hiệu) of poorly defined scope
    - Scope is TOO BIG: Unrealistic delivery expectations (people should agree with scope) -> slipping deadlines -> nervous designer + developers
        > should avoid this question during sprint: "can't we also have ...?"
    
    - Scope is TOO SMALL: unclear path to the full vision, haven't cover many things -> unremarkable, unimpressive, watered-down releases

    - Each extra feature make not _seem _like much, but put them all together -> to dần như quả bóng tuyết lăn -> you're on the way to crash

5. Scope and Strategy: Tradeoffs
> "Tradeoffs are essential to strategy. They create the need for choice, and they purposefully limit what a company offers"
> Michael Porter ("What is Strategy? Harvard Business Review")

Example: IKEA's strategic tradeoffs
    - has limted customer service -> intuitive shopping and lower prices (tradeoff ở đây là loại bỏ bớt 1 số nhân viên làm customer service...)
    - flat pack / knock-down furniture -> in-house, modern style and design
    - suburban loacations -> expansive on-site inventory

-> should figure out what you're gaining, what to give up

6. Delivering Continous Value
    - Scope includes figuring out how you'll systematically impress customers over the life of their relationship with the product
    - Scope includes figuring out how you'll systematically

7. Product Evolution: the long WOW - 4 basic steps:
    - 1st: Identify what your touchpoints for delivery are your platform recognized the places where you can combine the user experiences to deliver WOW.
        Number one is coordinate together to meet some need and can also sort of be remixed in a way to deliver a new solution to customers as you come up with them
        For example:
            Nike iPod sports kid combines 3 touchpoints:
                - The pedometer (1 thiết bị đeo tay): how do we engage 
                - The iPod
                - The Website
            Nike chooses 3 touchpoints to deliver on, not just one pedometer in your hand, it's your iPhone and web experience
            -> So it transcends the actual event
                Step 1 is how are we engage people, what are the points of contact, what are the points of interaction

    - 2nd: tackle wide area of unmet customer need

    - 3rd: Create a repeatable delivery process
        figure out what your approach í delivering regular consistent WOW moments
    
    - 4th: Plan and stage WOW experience

### Functional Specifications
> Start by asking why we're doing, what we're doing and we're asking what exactly are we going?

1. From Why To What
    - Từ việc biết được mục đích tổng thể của 1 product, cần xác định rõ các function cụ thể của product đó, từng function đó hoạt động như thế nào, **tương tác lẫn nhau** như thế nào

    - Mức độ chi tiết của requirements phụ thuộc vào scope: càng phức tạp thì càng nhiều requirement

    - Requirement cần được collect từ cả 2 phía: the client side (stake holders - người chủ dự án) và end user (người dùng cuối)
    - Các Requirements đc chia làm 3 loại (categories) sau:
        + There are things people say they need
        + There are things they actually need because those aren't always same things
        + There are things that they don't know they need

    1.1. Things that people say they need
        - Trong khi trao đổi với mọi người (stakeholders, end user), sẽ có rất nhiều ý kiến được đưa ra. Cần chú ý có nhiều ý kiến sẽ rất khó để thực hiện được (may be good ideas but they may not be possible): có thể không khả thi, khó thực hiện (difficult to accomplish), hoặc kéo dài timeline của dự án...
        - Nhiều người rất tự tin khi dự đoán tương lai nhưng thực sự có một sự khác biệt rất lớn giữa tưởng tượng dùng 1 sản phẩm như thế nào với việc thực sự sử dụng nó, nguyên nhân là bởi vì không có kinh nghiệm với sản phẩm hiện có, với dự án hiện có (đúng với những thứ mà chưa từng dùng bao giờ nên không thể miêu tả các function một cách hợp lý) -> điều này thay đổi hoàn toàn dự án
        - Lý do khác là những sở thích của con người thường không stable ("I don't mean that it's bad way. You know we're unstable creatures")

        -> Trong hầu hết trường hợp, hỏi mọi người về những lần sử dụng trong quá khứ hoặc suy đoán về việc sử dụng trong tương lai. Dù theo hướng nào thì cũng không đưa ra một danh sách các feature cụ thể, hoặc các possible outcomes. Không có gì khác ngoài các suy đoán lỏng lẻo về việc sản phẩm cần hoạt động như thế nào
        -> **đó là lý do vì sao những gì mọi người nói họ cần không phải luôn luôn là những gì họ thực sự cần, những gì họ nói họ sẽ làm không phải là luôn là gì những gì họ sẽ làm!!!**

    1.2 Things that people actually need
        When we have a problem, it can be effortless to imagine a solution that will solve it. However:
            - That solution will often address a **symptom** instead of the underlying problem
            - **Exploring** those suggsetions often leads to completely different requirements that solve the real problem

    1.3 Things that people don't know they need
        Các ý tưởng thường đến khi brainstorming, khi mà mọi người trao đổi cởi mở và tìm ra những ý tưởng (tìm ra trên whiteboard, )
        Trong khi brainstorm, cần focus vào cái kết quả cuối cùng là gì? cái outcome mọi người expect là gì?
    
    > "People don't want a quarter-inch drills - they want a quarter-inch holes" 

        Focus on the problem, instead of solutions

2. Create useful specification:
    Explore contextual **user scenarios** - it's a short, simple narratives that describe how someone might go about fulfilling a need
        -> cần làm việc với những người end user để xem nhu cầu thực sự của họ là gì, họ đang cố gắng đạt được gì
    
    Example: 1 Author cần qua những step sau để có content được published:
        Step 1: Author create or edit content, then submit for approval
        Step 2: Bus. Approver: review modification -> decline (return to step 1) or approve (next step)
        Step 3: Legal Approver: review -> decline (return to step 1) or approve (next step)
        Step 4: Site Admin: waiting to be published -> decline (return to step 1) or approve (next step)
        Step 5: go live
    
    2.1 3 specific rules to write useful specification:
        - Be positive: make positive statements as opposed to negative statements and that's simply because positive statements generally are much truer to a positive user experience and much more likely to result in a positive UX
            example:
                - don't want to say something like: "the system will not allow the user to purchase a fishing reel without fishing line" (negative -> don't do that)
                -> The system will suggest visiting the fishing line page if he tries to buy a fishing reel without line
                -> tạo ra một positive UX hơn là hiển thị error message không cho user purchase nếu không mua cả bộ

        - Be specific
            example:
                - The site will be accessible to disabled people (not specific)
                -> The site will contain inline audio help for people with impaired vision or blindness

        - Be objective (not subjective)
            example:
                - The site will be cool and hip (subjective) - to who??? (what's cool to me may not be cool to my 13 years old daughter)
                -> The site will conform to company brand guidlines

### Content Requirements
> Content is the information are coming to your site or using your app or your system in the first place. They can read, absorb, interact with this essentially content. There are a lot of different types of content

1. Content Requriements:

- Các loại content khác nhau thường kết hợp với nhau để thực hiện 1 single requirement
- Content có nhiều ảnh hưởng lớn tới hướng lựa chọn UXD
    + Content **format** and purpose
    + Size of each content type: word count, pixel dimensions, file size, bandwidth (for streaming video, audio)...
    + **Resources** needed to produce each type of content: for text - need writer, for image - need .. ? so in project team, someone need to be in charged of these tasks... (creating audio, video...) -> where do we store these contents... (in our server? in where ?)

2. Content Should Be **Strategic**

- User tìm đến sản phẩm (web, app...) dựa vào content thỏa mãn 2 tiêu chí sau:
    + appropriate for BUSINESS
    + appropriate for USERS
- Khi đã thỏa mãn cả 2, có những điều sau cần concernss:
    + cần có _DELIVERY METHOD_ tới users (how are we getting it to the audience) (save offline, retrieve online... ?)
    + cần có _STYLE & STRUCTURE_ : style: relax or formal, business? ...
    + cần có _SUBJECT & SUBSTANCE_

> your job is not to tell people how great you are or what you've accomplished or how long you've been in business or what's your positionin marketplace. Your job is tell them why any of that matters to them. "What's in it for me?"

- Your tasks:
    + Identify **content sources** as early as possible:
    + Identify **inappropriate content** as early as possible: là những thứ mà mọi người không quan tâm, content không còn đúng nữa,...
    + **Validate** every suggested content feature against the project's strategic objectives, need to tell a compelling story

- Remember that all content ideas sound great when **somebody else** is responsible for creating them!
- If design or development proceeds without content features and sourcing clerly **identified** and **validated**, the product is bound for failure

3. Content should be **contextual**
Content cần phụ thuộc vào ngữ cảnh của người đọc:
- PHYSICAL: DOING: Environment, stimuli, activity, habits, disabilities
    + user xem content ở trong phòng như thế nào? ồn ào hay tĩnh lặng? xem trên điện thoại hay đang đi trên phố, có tiếng ồn của traffic hay không...họ thích xem content ở đâu? (phone, tablet, laptop...?)
- EMOTIONAL: FEELING: psychological state, stress level, desires, wants, needs
- COGNITIVE: LEARNIGN: cognitive assumptions, learning ability, education

-> Because content should contextual, so Content Requirement should be contextual also -> it should be very-well defined, should be specific, shouldn't be subjective, shouldn't be subject to interpretation

Example:
    Question for client: What are your goals for this content?
    Client: It sells products
    ->Q: can you be more specific than that?
    ->A: it should sell a **specific** product
    ->Q: list and demonstrate the **benefits** of this product (more details)
    ->A: show how this product helps middle school teachers
-> đã có mô tả rõ hơn về product, 1 product cụ thể hướng đến các đối tượng rõ ràng

4. Content should be **user-centered**
- its purpose, its strategy, its form... should be depending on what kind of user is
Example:

Wrong way | Right way
------- | -------
design the site map to mirror the org chart | design the site map to reflect prioritized user needs
insist on using the client's internal mental models and vocabulary | Match users' model of the world and the ways they use specific terms and phrase (example: nếu customer gọi sản phẩm của mình là Screen Door, thì nếu mình gọi nó là Middle Door, Storm Door...là không cần thiết) -> cần phải match the way that your site visitor, your users think about those things
"We are a leading provider of blah.... | "Here's what's in it for you". "Here is why it's valuable for you..."

5. Ask the **right questions**
> "Useful", "Valuable" are the keywords when we talk about content

- Who is going to **create** all of this? 
- Who is going to approve all of this?
- Who is responsible for managing content, updating content?
- What are our competitors doing?
- Will people find this useful? valuable?
- How will people find all of this stuff? (content should not be too long, to complicated like a novel...)
- how many **different kinds of content** are there?
- Where does this fit in the **structure**?
- How are we going to **display** this? (and download it?)
- What are the **form factor** restriction? (on laptop, tablet,...?) (ví dụ content làm từ flash, mà flash ko chạy trên iPhone, trong khi iPHone chiếm 80% lượng target audience thì sao :D ?)

-> ask all questions to have a really solid leg up in managing all the potential headaches that content can cause
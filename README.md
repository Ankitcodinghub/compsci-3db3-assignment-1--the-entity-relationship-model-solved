# compsci-3db3-assignment-1--the-entity-relationship-model-solved
**TO GET THIS SOLUTION VISIT:** [COMPSCI_3DB3 Assignment 1- The Entity-Relationship Model Solved](https://www.ankitcodinghub.com/product/compsci_3db3-assignment-1-the-entity-relationship-model-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92598&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMPSCI_3DB3 Assignment 1- The Entity-Relationship Model Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Description

A local chain of cinemas has decided that their current information system is not sufficient in a modern world in which online ticket sales are the norm. As the first step to renew their system, the owner of the cinema approached a consultant firm that drafted requirements for the new information system. Following is the high-level description of these requirements.

First, the system will store information about several cinemas. Each cinema has a unique name and an address. In the past, cinema names have changed (e.g., due to renovations and grant reopenings). Per cinema, the system will also maintain information per room. Each room has a unique number within the cinema (e.g., smaller cinemas have Room one to Room five). Per room, the system can keep track of the characteristics of the cinema installation. These characteristics include

<ol>
<li>the screen type (e.g., normal, purpose-built IMAX, digital IMAX) and screen size;</li>
<li>the projector type (e.g., analog or digital, resolutions, supported 3D modes, 48FPS, and so on);</li>
<li>the sound system (e.g., the number of speakers and the supported sound options such Dolby Atmos, Dolby Digital, and DTS); and</li>
<li>the available accessibility options.</li>
</ol>
This information is not only available for cinema visitors, but will also be communicated to private parties that are looking to hire a room (e.g., for a corporate event). Finally, per room the system also needs to know the exact seat arrangement, as the online system will allow customers to order tickets for specific seats. Hence, the system keeps track, per room, of each seat and—per seat—its location in the room, the row it is in, and the seat number (within the row). Furthermore, some seats are standard reserved for disabled people.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Second, the system needs to store information for each screening. Each screening is assigned a single room and timeslot and the system distinguishes between three types of screenings: normal screenings will show a single film and will be offered via normal ticket prices; special screenings can show one-or-more films with a special ticket price, e.g., a marathon with a higher ticket price or a classic film at a reduced ticket price; and private screenings (as part of hired rooms). For each public screening, the system keeps track which films are shown. This film information is provided by the film distributors in a standard format: for now, the system represents this external information via an entity Film with an attribute fid. If a screening will show multiple films (as part of special screening), then each of these films will be shown in the same room and the ticket of the customer assign the same seat during each film.

Finally, and most importantly, the system will support sales and reservation. Via an (online) sale, customers can buy one or more tickets for a specific screening and that are assigned a seat on sale. Customers that do not feel comfortable with paying online can reserve their seats online and buy a ticket for these reservations at the counter (these reservations will be cancelled 45 minutes before the start of the film). For each sale, we keep track of how they are made (online, ticket machine, at the counter) and whether the sale was related to a reservation. The cinema chain owners plan to analyze this data to see what factors influence the willingness of customers to buy and reserve tickets via their online system. Furthermore, we keep track of the paid price (which can depend on coupons, special actions, payment method, or room and film options).

Assignment

The goal of the assignment is to present the above requirements for an information system into an ER (entity- relationship) diagram. To do so, you have to write a report in which you translate the above requirements into an ER (entity-relationship) diagram. Your submission:

<ol>
<li>must be a PDF file;</li>
<li>must include an analysis of the requirements of the information system: which parts of the above description are important, which parts did you ignore, which constraints did the requirements provide, which of these constraints did you incorporate in the ER diagram, and which constraints did you exclude (and motivate why they are excluded);</li>
<li>must provide a readable and complete presentation of your ER-diagram (that matches your analysis, any discrepancies between your analysis and the resulting ER-diagram should be explained); and</li>
<li>must have ER-diagrams that are drawn using software (hand-drawn and scanned submissions will not be graded); big diagrams can be submitted as a separate PDF, PNG, or GIF alongside the report.</li>
</ol>
Submissions that do not follow the above requirements will get a grade of zero.

Grading

While evaluating your work, we will look at:

completeness Does your diagram contain all entities, attributes, relationships, and (if possible) constraints described in the requirements?

correctness Does your diagram use the correct notation and do you take the right design decisions? Are all included constraints correct? Do all excluded constraints have a proper motivation?

presentation Is the diagram and the report readable? Is the report presentable as a stand-alone report to an external party (e.g., the cinema chain owners)?

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
In specific, the presented report will account for 10% of the maximum grade; the required entities, attributes, and relationship will account for 60% of the maximum grade; and the required constraints (e.g., keys, relationship participations) will account for 30% of the maximum grade. Every error and inconsistency in your ER-diagram notation will result in a reduction of the overall grade (with the lowest possible grade being zero).

Remarks on drawing ER-diagrams

There are plenty of modelling and drawing programs that support the creation of beautiful ER-diagrams. Most programs will use a notation that is slightly different from the textbook and the slides, however. You are allowed to use such a different notation, but if you do so: make clear what notation you exactly use (e.g., specify what each type of arrow that you draw means) and stick to a single notation.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>

# wireless-and-mobile-networking-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [Wireless-And-Mobile-Networking Homework 3 Solved](https://www.ankitcodinghub.com/product/wireless-and-mobile-networking-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99717&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Wireless-And-Mobile-Networking Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem description

19 base stations are located in an urban area with temperature 27°C, which form a 19-cell map shown in Fig. 1. The coordination of the central BS is (0, 0) and ISD (inter site distance) is 500 m. The channel bandwidth is 10MHz. All BSs use the same carrier frequency (frequency reuse factor =1).The power of each base station is 33dBm. The power of each mobile device is 23dBm. The transmitter antenna gain and the receiver antenna gain for each device, including base station and mobile devices, are 14 dB. The height of each base station is 1.5m, which is located on the top of a 50m high building. The position of each mobile device is 1.5m high from the ground.

</div>
</div>
<div class="layoutArea">
<div class="column">
Fig. 1

</div>
<div class="column">
Fig. 2

</div>
</div>
<div class="layoutArea">
<div class="column">
Consider the path loss only radio propagation (without shadowing and fading). Use Two-ray-ground model as the propagation model for your simulation.

HINT: Please refer to slide 52 of Lec 2 for two-ray-ground model.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
In this homework, the bonus problem is more difficult. If you want to get the bonus, you

don’t need to submit problem 1.

1. [1 moving mobile device, downlink]

In this problem, only downlink case is considered in this system. There are mobile devices doing downlink communication in all the cells. We only consider 1 mobile device which moves based on random walk mobility model as described below.

Random walk mobility model

<ol>
<li>The mobile device chooses the moving direction between [0, 2π] uniformly.</li>
<li>The mobile device chooses the velocity between [minSpeed, maxSpeed] uniformly.</li>
<li>Based on the chosen direction and velocity, the mobile device moves t seconds, in which t is
chosen uniformly between [minT, maxT].
</li>
<li>Upon arriving the destination, the mobile device chooses another direction, velocity and travel
time again according to step a, b and c.
</li>
</ol>
In this problem, please use the parameter setting in Table 1. Table 1

minSpeed 1 m/s maxSpeed 15 m/s minT 1s maxT 6s

The initial location of the mobile device is (250, 0).

Total simulation time is 900 seconds.

Since the 19-cell map is symmetric, if the mobile device reaches the map boundary, it will enter the opposite cell as shown in Fig. 2. That is, from the mobile device perspective, the map seems to extend.

<ol>
<li>1-1. &nbsp;Please give a figure to describe how you arrange cell IDs to Fig. 1. HINT: Cell IDs should be 1~19 for simplicity.</li>
<li>1-2. &nbsp;Based on 1-1, please list all the time when the handoff event occurs and the related cell ID following the below format:</li>
</ol>
Time Source cell ID Destination cell ID 3s 1 2

It means at the 3rd second, the mobile device moves from cell 1 to cell 2.

HINT: The criteria to decide when the handoff events occur can be either coordination-based or SINR-based. You SHOULD define your criterion in your report.

1-3. How many handoff events happen during the total simulation time?

※ If the simulation time is not long enough for the handoff events to occur, you can increase the simulation time and describe the simulation time you set in the report.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
BONUS !!!

[100 moving mobile device, uplink]

In this problem, only uplink case is considered. 100 mobile devices do uplink communication and moves based on random walk mobility model as described below.

Random walk mobility model

<ol start="5">
<li>The mobile device chooses the moving direction between [0, 2π] uniformly.</li>
<li>The mobile device chooses the velocity between [minSpeed, maxSpeed] uniformly.</li>
<li>Based on the chosen direction and velocity, the mobile device moves t seconds, in which t is
chosen uniformly between [minT, maxT].
</li>
<li>Upon arriving the destination, the mobile device chooses another direction, velocity and travel
time again according to step a, b and c.
</li>
</ol>
In this problem, please use the parameter setting in Table 1. Table 1

minSpeed 1 m/s maxSpeed 15 m/s minT 1s maxT 6s

The initial locations of all the 100 mobile devices are decided uniformly in the 19-cell map.

Total simulation time is 900 seconds.

Since the 19-cell map is symmetric, if the mobile device reaches the map boundary, it will enter the opposite cell as shown in Fig. 2. That is, from the mobile device perspective, the map seems to extend.

<ol>
<li>B-1 &nbsp;Please give a figure to describe how you arrange cell IDs to Fig. 1. HINT: Cell IDs should be 1~19 for simplicity.</li>
<li>B-2 &nbsp;Please plot a map with all mobile devices in their initial location. Describe how you decide the initial location.</li>
<li>B-3 &nbsp;Based on B-1, please list all the time when the handoff event occurs and the related cell ID following the below format:</li>
</ol>
Time Source cell ID Destination cell ID 3s 1 2

It means at the 3rd second, the mobile device moves from cell 1 to cell 2.

HINT: The criteria to decide when the handoff events occur SHOULD be SINR-based. You SHOULD describe your criterion clearly in your report.

B-4 How many handoff events happen during the total simulation time?

※ If the simulation time is not long enough for the handoff events to occur, you can increase the simulation time and describe the simulation time you set in the report.

</div>
</div>
</div>

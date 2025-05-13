# cse-330--assignment-2-semaphores-solved
**TO GET THIS SOLUTION VISIT:** [CSE 330 –Assignment: #2 Semaphores Solved](https://www.ankitcodinghub.com/product/cse-330-assignment-2-semaphores-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;8083&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 330 –Assignment: #2 Semaphores Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="product-description">Q1] Suppose a system has an atomic hardware instruction SHIFT, that does the

follows:

SHIFT ( int *A, *B ) {

*B =*A; // ATOMICALLY

*A = 0

}A] Implement Dijkstra style semaphores with the shift instruction, that is,

semaphores which utilize busy waiting.B] Implement blocking semaphores using the shift instructions.Q2] There are 4 processes, executing concurrently. Process P0 is in an infinite loop, incrementing the value of the variable x (x is initialized to 0). P0 is the only process that changes the value of x.The rest of the processes Pi (1&lt;= i &lt;=3) monitor the value

of x. Whenever x reaches a value such that it is divisible by i, Pi prints the value

of x. For example, P3 will print the sequence 3 6 9 12 ….. as the value of x reaches 3, 6, 9, 12 and so on.Write the code for all the 4 processes using semaphores. Note that P1 – P3 should be identical; also Pi determines whether x is to be printed, and this decision is not

made by P0.

Q3] A synchronization mechanism consists of 2 atomic routines, ENQ(r) and DEQ(r).

“r” is a resource variable that has two fields, inuse (boolean) and queue (a queue)

which is a queue of processes waiting to acquire the resource. The definitions ofENQ and DEQ are:

ENQ(r) : if (r.inuse==1) then begin

insert current process in r.queue

block

end

else r.inuse = 1;

DEQ(r) : if r.queue == nil then inuse = false

else delete a process from r.queue and activate it.Construct an implementation of ENQ/DEQ using semaphores. You can use other

variables, etc that you need, but no other atomic code or synchronization constructs other than P or V can be used.

Q4]

Do the reverse of Q3, that is implement Semaphores using ENQ/DEQ.

</div>

<style type="text/css">
    .profiles {
        gap: 1rem;
        flex-wrap: wrap;
        padding: 1rem;
        justify-content: center;
    }
    .profile {
        max-width: 300px;
        min-width: 170px;
        text-align: left;
        padding-bottom: 1rem;
    }
    .profile-photo {
        width: 100%;
        height: 400px;
        object-fit: cover;
        margin-top: 0;
        border-radius: 5px;
    }

    .seahawks-card {
        margin: 0 auto;
        max-width: 700px;
    }
    .seahawks-photo {
        width: 50%;
        height: auto;
        margin: 0;
        margin-right: 20px;
        object-fit: contain;
    }
    .profile-body {
        padding-left: 1rem;
    }

    @media (max-width: 800px) {
        .profile-photo {
            height: 350px;
        }
        .seahawks-photo {
            width: 100%;
            height: auto;
        }
    }
    img {
        border-radius: 10px;
    }
</style>

<h1 class="pt-10 text-center">Help us run in the NYC Marathon!</h1>
<p>Hello! The three of us have decided to run in the New York City Marathon this year and we could not be more excited to participate in such an incredible experience. In order to run in the marathon, we need your help! To earn a spot in the race, we each need to raise at least $3,000 for a charity of our choosing.</p>
<p>To raise this money, we've decided to create a lottery to win two tickets to a Seahawks game! View below for details on entry and to see how this directly helps us reach our goal.</p>
<a
    class="btn btn-primary"
    href="https://buy.stripe.com/fZe4jYaaGaZmc7K144">
    Enter The Lottery
</a>
<h1 class="pt-20">Meet the Runners</h1>
<p>You can choose to enter the lottery for a chance to win Seahawks tickets, or you can also donate directly to each of us. A link to our charity pages can be found below.</p>
<div class="flex profiles">
    <div class="profile card bg-base-100 shadow-xl">
        <img
            class="profile-photo"
            alt=""
            src="james-marathon.png" />
        <div class="profile-body">
            <h3 class="mt-2">James Evans</h3>
            <p>Donate to James' charity: <a href="https://donate.parentprojectmd.org/fundraiser/4490184">The Parent Project</a></p>
            <!-- The button to open modal -->
            <label
                class="btn"
                for="my_modal_1">About James</label>

            <!-- Put this part before </body> tag -->
            <input
                id="my_modal_1"
                class="modal-toggle"
                type="checkbox" />
            <div class="modal">
                <div class="modal-box">
                    <h3 class="font-bold text-lg">Hello!</h3>
                    <p class="pt-4"> I'm James and I will be running in the 2023 New York City marathon. Throughout this year as I train, I'll be raising money with the Parent Project to end Duchenne muscular dystrophy. If you didn't know, Duchenne muscular dystrophy is a genetic disorder characterized by the progressive loss of muscle. It is a multi-systemic condition, affecting many parts of the body, which results in deterioration of the skeletal, heart, and lung muscles.
                    <p>Running is a new hobby of mine, and I have found it to be incredibly moving to see people of all backgrounds and abilities put in the time and effort to be able to run an entire marathon.</p>
                    <p class="pb-4">Any donations, big or small, are greatly appreciated. Thanks so much for your support, and please don't forget to send this page to any friends you think might be interested in donating!</p>
                    <div class="modal-action">
                        <label
                            class="btn"
                            for="my_modal_1">Close!</label>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="profile card bg-base-100 shadow-xl">
        <img
            class="profile-photo"
            alt=""
            src="lauren-marathon.jpeg" />
        <div class="profile-body">
            <h3 class="mt-2">Lauren Sanford</h3>
            <p>Donate to Lauren's charity: <a href="https://fundraisers.hakuapp.com/lauren-sanford?fbclid=IwAR0gdkMWrWPpmbbMSrypkI6LFQqDgFvJCju-Y9CRLA0c3z0WojaikzM3QXA">Camp Korey</a></p>
            <!-- The button to open modal -->
            <label
                class="btn"
                for="my_modal_2">About Lauren</label>
        
            <!-- Put this part before </body> tag -->
            <input
                id="my_modal_2"
                class="modal-toggle"
                type="checkbox" />
            <div class="modal">
                <div class="modal-box">
                    <h3 class="font-bold text-lg">Hi!</h3>
                    <p class="py-4">I am so excited to share that I am running in the TCS New York City Marathon to raise funds in support of Camp Korey. Their mission is to honor the courage, strength, and determination of children living with life-altering medical conditions and their families by providing them with a transformational experience in a fun, safe camp environment with specialized medical support. This camp is close to my heart as a speech therapist because I work with children who need a high level of support to participate in everyday fun activities, like camp. I have also witnessed the value of providing respite for their parents and caregivers during everyday life. Camp Korey adapts each week for kids and their families to enjoy a camp experience, without the limitations that they may face in our world. Your donation helps provide campers with accessible, adaptive year-round programs, always 100% free to campers. Thank you!</p>
                    <div class="modal-action">
                        <label
                            class="btn"
                            for="my_modal_2">Close!</label>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="profile card bg-base-100 shadow-xl">
        <img
            class="profile-photo"
            alt=""
            src="kelsea-marathon.jpeg" />
        <div class="profile-body">
            <h3 class="mt-2">Kelsea Willenbrock</h3>
            <p>Donate to Kelsea's charity: <a href="https://www.facebook.com/donate/6145020998883723/3550431058522891/">American Cancer Society</a></p>
            <!-- The button to open modal -->
            <label
                class="btn"
                for="my_modal_3">About Kelsea</label>
        
            <!-- Put this part before </body> tag -->
            <input
                id="my_modal_3"
                class="modal-toggle"
                type="checkbox" />
            <div class="modal">
                <div class="modal-box">
                    <h3 class="font-bold text-lg">Hi!</h3>
                    <p class="pt-4">I have been a runner since I was in high school and over the years the sport has played various roles in my life. Running has afforded me the opportunity to compete, build lasting friendships, explore both new and familiar places, learn how to keep my body healthy, and now to support an organization that makes a real difference in the lives of cancer patients and their families.</p>
                    <p>I ran the New York City Marathon in 2022 and was blown away by the electric atmosphere along the course, but was especially inspired by the countless participants who were running for a specific cause. I cannot wait to hit the streets of my favorite city this November in support of the American Cancer Society in honor of my mom, a colon cancer survivor.</p>
                    <p>In 2021, my Mom received the news that her routine colonoscopy had come back cancerous. Thankfully, after a sucessful surgery and 6 months of bi-weekly Chemotherapy treatment, she was deemed cancer free. After this season, my family has a renewed appreciation for health and the ability to participate in life with few limitations.</p>
                    <p>Cancer is not something that anyone expects to be a part of their story, but it affects so many. Funds raised for the American Cancer Society support cancer patient programs and groundbreaking research that can help save lives. I'm excited to be using the platform of the 2023 New York City Marathon to contribute my small part to end cancer as we know it, for everyone.</p>
                    <p class="pb-4">Thank you for your support, whether financially or prayfully over the training process :)</p>
                    <div class="modal-action">
                        <label
                            class="btn"
                            for="my_modal_3">Close!</label>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<h1 class="text-center mt-20">Enter to win 2 tickets to the Seattle Seahawks!</h1>

<div class="flex py-6 justify-content-center seahawks-card flex-wrap p-3">
    <img
        class="seahawks-photo"
        alt=""
        src="seahawks-browns.png" />
    <div class="text-left">
        <h1 class="mb-0">Seattle Seahawks</h1>
        <p class="my-0">vs.</p>
        <h1 class="mb-0">Cleveland Browns</h1>
        <h3 class="mt-2">Oct. 29th</h3>
    </div>
</div>

<p>Enter for a chance to win Seahawks tickets! Each $10 entry to the lottery earns you another chance to win two tickets to watch the Seattle Seahawks play the Cleveland Browns on October 29th!</p>
<p>Remember, more entries = more chances to win those tickets! All proceeds to the lottery goes directly towards our charities. This is an awesome way to give back to communities in need, and to help us reach our goal to run in the New York City Marathon!</p>
<a
    class="btn btn-primary"
    href="https://buy.stripe.com/fZe4jYaaGaZmc7K144">
    Enter The Lottery
</a>

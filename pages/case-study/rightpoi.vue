<template>
  <main>
    <section class="text-center">
      <!-- <div class="px-4 md:px-0">
        <h1 class="text-5xl font-bold leading-tight md:leading-none">
          Content Marketing
        </h1>
        <h3 class="text-base">
          A collaborative space to plan, produce, and publish omnichannel
          campaigns
        </h3>
      </div> -->
      <img
        src="/case-study/rightpoi.svg"
        alt="Rightpoi.."
        class="overflow-hidden"
      />
    </section>
    <div class="bg-white">
      <section
        class="container pt-8 mt-12 mx-auto md:pt-8 md:grid md:gap-8 lg:gap-20 md:grid-cols-2"
      >
        <div>
          <h4 class="text-2xl font-bold uppercase">OVERVIEW</h4>
          <div class="text-base text-dark-gray">
            <!-- <p class="mt-4">
              My most recent work with
              <a href="#" class="font-bold text-pink">Emerhub</a> where I
              designed for some of its core offerings like Incorporation,
              Payroll, Registry with a global reach that helped integrate all
              their needs under one roof. Having led the module phase for one
              years in this young,
            </p> -->
            <p class="mt-6">
              India's western coastal area; especially Mangalore, Udupi &
              Kundapur is full of private buses carrying people everyday,
              travelling 150km via multiple routes. There are almost 200+ buses
              travel at regular interval. It is very difficult for the people
              who commute often in bus to know the timings and routes. So, I
              decided to take up this challenge and design a mobile app which
              help the users with timings and routes with the add-on features
              like rating and comments.
            </p>
            <p class="mt-6">
              <strong
                >In a regional language i.e. Tulu, Rightpoi means Let's
                Go!</strong
              >
            </p>
            <p class="mt-6">
              <strong>Primary goal was:</strong>
            </p>
            <ul class="bullets">
              <li>Understand user goals and pain points</li>
              <li>Target people who often commute</li>
              <li>App should be easy and simple to use</li>
            </ul>
          </div>
        </div>
        <div>
          <h4 class="text-2xl font-bold uppercase">ROLE & DURATION</h4>
          <div class="px-4 mt-6">
            <h6 class="text-base font-bold">Product UX/UI Designer</h6>
            <p class="mt-2 text-sm text-dark-gray">
              Research, Interview, User Journey, Prototyping, Visual design &
              testing
            </p>
          </div>
          <div class="mt-4 text-sm text-dark-gray">
            <p class="px-4 py-4 bg-gray">OCT, 2015</p>
          </div>
        </div>
      </section>
      <section class="py-12 mt-20 text-white bg-rightpoi md:py-20">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Part of a design challenge
            </h2>
            <p class="mt-8">
              I am not in any way affiliated to Grab or any other
              companies/individuals mentioned in this article. The design
              decisions and assumptions taken in this case study are solely
              based on publicly available information.
            </p>
          </div>
        </div>
      </section>
      <section class="py-8 mt-8 md:py-16">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Research phase
            </h2>
            <p class="mt-8">
              It is my first ever on field research in the city. At this phase,
              I conducted user interviews in order to get a better understanding
              of the problem.
            </p>
            <h6 class="mt-8"><strong>Preliminary Questions:</strong></h6>
            <ul class="mt-4 bullets">
              <li>What is your age?</li>
              <li>How often you travel in bus and why?</li>
              <li>What is the average duration to commute?</li>
              <li>How you find bus timing/route/bus number?</li>
              <li>Motivation/Pain points while commuting.</li>
              <li>Do you have anything to add?</li>
            </ul>
          </div>
          <img
            src="/case-study/right-research.jpg"
            alt="research"
            class="overflow-hidden mt-8"
          />
        </div>

        <!-- <div class="md:container md:mx-auto">
          <no-ssr>
            <vue-tiny-slider v-bind="tinySliderOptions" class="mt-8">
              <img src="/case-study/slider/slider1.png" alt="Slide 1" />
              <img src="/case-study/slider/slider1.png" alt="Slide 2" />
              <img src="/case-study/slider/slider1.png" alt="Slide 3" />
              <img src="/case-study/slider/slider1.png" alt="Slide 4" />
            </vue-tiny-slider>
          </no-ssr>
        </div> -->
      </section>
      <section class="py-20 mt-8 bg-gray">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Interviews
            </h2>
            <p class="mt-8">
              One important thing I got to know from interview, even regular
              commuters are want to know
              <strong>where is the bus now?</strong> Though they are very much
              sure with the timing & route, they want to know at which location
              the bus is travelling now(via Google map) so that they are well
              prepared to catch the bus in next bus stop.
              <strong>Well, thats an amazing feature!</strong>
            </p>
            <p class="mt-8">
              But I decided to go with
              <strong> Minimum Viable Product(MVP) </strong> for the first time.
            </p>
            <p class="mt-8">Few other response I got:</p>

            <div class="px-8 mt-8 py-6 bg-white border-l-4 border-blue-300">
              <p class="text-gray-500">
                “I think there are lot of bus travel from this particular
                routes. So it's ok to stand in bus-stop and wait. (Not
                interested to check in App)”
              </p>
              <p class="mt-2 text-sm">Devdas Kamath ( Daily Commuter )</p>
            </div>
            <div class="px-8 mt-8 py-6 bg-white border-l-4 border-blue-300">
              <p class="text-gray-500">
                “I want to know the bus number and timing as soon as I type the
                destination.”
              </p>
              <p class="mt-2 text-sm">Unknown</p>
            </div>
            <div class="px-8 mt-8 py-6 bg-white border-l-4 border-blue-300">
              <p class="text-gray-500">
                “ I want to know the bus fare and total time to reach the
                destination.”
              </p>
              <p class="mt-2 text-sm">Ranjitha (Student)</p>
            </div>
          </div>
        </div>

        <!-- <div class="container mt-2 text-sm md:text-center text-dark-gray">
          Fig: Competitive Analysis to identify best practices and opportunity
          areas.
        </div> -->
      </section>
      <!-- <section class="container items-start py-8 mx-auto mt-8 md:py-16 md:flex">
        <div class="md:w-1/2">
          <h2 class="text-5xl font-bold leading-tight md:leading-none">
            Jumpstarting Research
          </h2>
          <p class="mt-8">
            My most recent work with
            <a href="#" class="font-bold text-pink">Emerhub</a> where I designed
            for some of its core offerings like Incorporation, Payroll, Registry
            with a global reach that helped integrate all their needs under one
            roof. Having led the module phase for one years in this young,
          </p>
        </div>
        <div class="md:w-1/2 md:pl-8">
          <img
            class="mx-auto mt-8 md:h-full md:overflow-hidden md:mt-0"
            src="/case-study/slider/slider1.png"
            alt="Slide 4"
          />
        </div>
      </section> -->
      <section class="py-8 mt-8 md:py-16">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              User Journey
            </h2>
          </div>
        </div>
        <div class="large-container">
          <img
            src="/case-study/right-user-journey.jpg"
            alt="User journey map"
            class="overflow-hidden mt-8 mx-auto"
          />
        </div>
      </section>
      <section class="py-20 mt-8 bg-gray">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Information Architecture
            </h2>
            <p class="mt-8">
              Then I came up with application flow diagram which was a
              representation of all the common user needs, goals, tasks that I
              derived from the user interviews.
            </p>
          </div>
          <img
            class="mt-12"
            src="/case-study/right-info-architect.jpg"
            alt="Information architecture"
          />
        </div>

        <!-- <div class="container mt-2 text-sm md:text-center text-dark-gray">
          Fig: Competitive Analysis to identify best practices and opportunity
          areas.
        </div> -->
      </section>
      <section class="py-20 mt-8">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Prototype
            </h2>
          </div>
        </div>
        <div class="large-container mx-auto">
          <img
            class="mt-12"
            src="/case-study/right-proto.jpg"
            alt="Prototype"
          />
        </div>
        <!-- <div class="container mt-2 text-sm md:text-center text-dark-gray">
          Fig: Competitive Analysis to identify best practices and opportunity
          areas.
        </div> -->
      </section>
      <section class="mt-8 large-container mx-auto">
        <img src="/case-study/Right-UI-1.jpg" alt="Diet tracker UI" />
        <img src="/case-study/Right-UI-2.jpg" alt="Diet tracker UI" />
        <img src="/case-study/Right-UI-3.jpg" alt="Diet tracker UI" />
        <img src="/case-study/Right-UI-4.jpg" alt="Diet tracker UI" />
      </section>
      <section class="py-20 mt-8">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Usability Testing
            </h2>
            <p class="mt-12">
              I've made a Mobile app (prototype) testing round in order to
              reveal possible usability problems. I have tested the prototype
              with my friends, family members and colleagues.
            </p>

            <ul class="bullets mt-8">
              <li>
                Major usability issue was with the Time input. Painful process
                to input time range(from & to). <strong>Solution:</strong> Kept
                single input box for both from and to with the dropdown to
                select time and minutes. Inspiration : Android alarm settings.
              </li>
              <li>
                Few CTA texts changed : 'Go' to ' Find'. 'Start' to 'Rightpoi'.
              </li>
              <li>There were other remarks regarding font size and colors.</li>
              <li>At last, drastic changes in the actual design :)</li>
            </ul>
          </div>
        </div>
      </section>
      <section class="py-20 mt-8 bg-gray">
        <div class="container">
          <div class="mx-auto md:w-10/12">
            <h2 class="text-5xl font-bold leading-tight md:leading-none">
              Project Learnings
            </h2>

            <p class="mt-8 text-dark-gray">
              This is my first ever individual project without any Business
              model, Technology constraints, Brand Identity in-front. It has
              been a big learning curve for me. I learned to listen people and
              understood prototype is a powerful tool.
            </p>
          </div>
        </div>
      </section>
      <section class="container pt-20 text-center border-t border-gray">
        <h4 class="text-base font-bold uppercase">MORE PROJECTS</h4>
        <div class="grid grid-cols-2 gap-4 py-8 md:gap-8 md:grid-cols-4">
          <nuxt-link to="/case-study/incorporation">
            <img
              class="w-full rounded-2xl"
              src="/case-study/Inc-small-thumb.jpg"
              alt="Payroll"
            />
          </nuxt-link>
          <nuxt-link to="/case-study/payroll">
            <img
              class="w-full rounded-2xl"
              src="/case-study/Pay-small-thumb.jpg"
              alt="Payroll"
            />
          </nuxt-link>
          <nuxt-link to="/case-study/diet-tracker">
            <img
              class="w-full rounded-2xl"
              src="/case-study/Diet-small-thumb.jpg"
              alt="Diet Tracker"
            />
          </nuxt-link>
          <nuxt-link to="/case-study/logo-designs">
            <img
              class="w-full rounded-2xl"
              src="/case-study/Mk-small-thumb.jpg"
              alt="Logo Designs"
            />
          </nuxt-link>
        </div>
      </section>
    </div>
  </main>
</template>

<script>
export default {
  data() {
    return {
      tinySliderOptions: {
        autoplay: true,
        mouseDrag: true,
        loop: true,
        items: 1,
        swipeAngle: 45,
        controls: false,
        navPosition: 'bottom',
      },
    }
  },
}
</script>

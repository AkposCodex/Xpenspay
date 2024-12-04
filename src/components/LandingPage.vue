<script>
export default {
  name: 'LandingPage',
  methods: {
    handleSubmit(event) {
      event.preventDefault();
      // Form submission logic would go here
    }
  }
}
</script>
<template>
  <div class="flex overflow-hidden flex-col bg-white">
    <header class="flex flex-col w-full max-md:max-w-full">
      <nav
        class="flex overflow-hidden flex-col py-0.5 pr-16 pl-7 w-full max-md:px-5 max-md:max-w-full"
        role="navigation"
        aria-label="Main navigation"
      >
        <div
          class="flex flex-wrap gap-5 justify-between max-w-full text-lg font-medium text-center text-black w-[898px] max-sm:mx-auto"
        >
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/6a21e9e92c25a36bb6144942c9b9e60e3351226a0fdb4687a4f2b830305470d8?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
            class="object-contain shrink-0 max-w-full aspect-[4.1] w-[197px] max-sm:mx-auto"
            alt="Xpenspay Logo"
          />
          <div class="flex gap-6 items-center my-auto">
            <a
              href="#home"
              class="flex-1 shrink gap-2.5 self-stretch my-auto font-bold whitespace-nowrap border-b border-black w-[57px]"
            >
              Home
            </a>
            <a href="#about" class="self-stretch my-auto">
              About
            </a>
            <a href="#become-agent" class="self-stretch my-auto">
              Become an agent
            </a>
          </div>
        </div>
      </nav>
    </header>

    <main class="flex flex-col">
      <section
        class="self-end mt-20 w-full max-w-[1360px] max-md:mt-10 max-md:max-w-full"
        aria-label="Hero section"
      >
        <div class="flex gap-5 max-md:flex-col">
          <div class="flex flex-col w-[34%] max-md:ml-0 max-md:w-full">
            <img
              loading="lazy"
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/3e6706bff0e5f2f2fc01c2590465134e29e634c237102dd2e59d72afbd0ee055?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
              class="object-contain grow w-full aspect-[0.87] max-md:mt-10 max-md:max-w-full"
              alt="Mobile payment illustration"
            />
          </div>
          <div class="flex flex-col ml-5 w-[38%] max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col items-start self-stretch my-auto text-center text-black max-md:mt-10 max-md:max-w-full"
            >
              <h1
                class="text-5xl font-bold max-md:max-w-full max-md:text-4xl"
              >
                Discover a new way to pay
              </h1>
              <p class="mt-6 text-2xl font-medium max-md:max-w-full">
                Stop worrying about small change and start using Xpenspay
                today
              </p>
            </div>
          </div>
          <div class="flex flex-col ml-5 w-[27%] max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col self-stretch my-auto text-lg font-medium text-center text-black max-md:mt-10"
            >
              <div
                class="flex shrink-0 rounded-2xl border-cyan-500 border-dashed border-[13px] h-[332px]"
                role="img"
                aria-label="QR Code for app download"
              ></div>
              <p class="self-center mt-2.5">Scan to download the app</p>
            </div>
          </div>
        </div>
      </section>

      <section
        class="flex flex-col items-center px-16 pt-5 pb-8 w-full text-2xl font-medium text-white bg-cyan-500 max-md:px-5 max-md:max-w-full"
        aria-label="Partner information"
      >
        <div class="flex flex-wrap gap-1 items-end ml-5 max-md:max-w-full">
          <p
            class="max-md:max-w-full max-sm:mx-auto max-sm:mb-auto max-sm:text-center"
          >
            A Product of Direct Distribution Crafts llc. Powered by
          </p>
          <div class="flex items-end min-w-[240px]">
            <img
              loading="lazy"
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/57ebeb0401582b719bc27f3540e484cd3d01630da939e672432cb3e5b8a2df13?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
              class="object-contain shrink-0 aspect-[1.18] w-[39px]"
              alt="VFD Microfinance Bank logo"
            />
            <span>VFD Microfinace Bank</span>
          </div>
        </div>
      </section>

      <section
        class="flex flex-col items-center mt-14 w-full max-md:mt-10 max-md:max-w-full"
        aria-label="Features section"
      >
        <div
          class="flex flex-wrap gap-10 justify-between items-center max-w-full w-[1392px] max-sm:px-4 max-sm:mx-4"
        >
          <div
            class="flex flex-col self-stretch my-auto text-black min-w-[240px] w-[827px] max-md:max-w-full"
          >
            <h2
              class="text-5xl font-bold max-md:max-w-full max-md:text-4xl max-sm:mx-auto max-sm:text-center"
            >
              Easily find merchants around you on the xpenspay platform
            </h2>
            <p
              class="mt-5 text-2xl font-medium max-md:max-w-full max-sm:text-center"
            >
              Make sure you get the fastest possible service wherever you go,
              hassle-free
            </p>
          </div>
          <div
            class="flex overflow-hidden flex-col self-stretch px-1 my-auto min-w-[240px] w-[390px]"
          >
            <img
              loading="lazy"
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/e04dcbff994243f2fb8f37b5e9b54e0105dc1832d935c7158849e8fe76c1e82b?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
              class="object-contain w-full aspect-[0.66]"
              alt="Merchant locator feature illustration"
            />
          </div>
        </div>
      </section>

      <section class="agent-signup mt-28 max-md:mt-10" aria-label="Agent signup">
        <div
          class="flex flex-wrap gap-10 justify-between items-start max-w-full w-[1392px] max-sm:mx-auto"
        >
          <div class="flex flex-col min-w-[240px] w-[827px] max-md:max-w-full">
            <div
              class="flex flex-col w-full text-black max-md:max-w-full max-sm:px-4"
            >
              <h2 class="text-4xl font-bold max-md:max-w-full">
                Become an Xpenspay Agent by attending our Agent activation event.
              </h2>
              <p class="mt-3 text-lg font-light max-md:max-w-full">
                You will receive an SMS or email regarding the date and location
                of the event.
              </p>
            </div>
            <form
              class="flex flex-col mt-6 max-w-full text-lg w-[690px] max-sm:mx-auto max-sm:text-center"
            >
              <div class="flex flex-col w-full font-light text-black max-md:max-w-full max-sm:px-4">
                <div class="mb-4">
                  <label for="name" class="sr-only">Name</label>
                  <input
                    type="text"
                    id="name"
                    name="name"
                    class="gap-2.5 self-stretch p-2.5 w-full whitespace-nowrap rounded border border-solid border-zinc-400 max-md:max-w-full"
                    placeholder="Name"
                    required
                  />
                </div>
                <div class="mb-4">
                  <label for="phone" class="sr-only">Phone number</label>
                  <input
                    type="tel"
                    id="phone"
                    name="phone"
                    class="gap-2.5 self-stretch p-2.5 w-full rounded border border-solid border-zinc-400 max-md:max-w-full"
                    placeholder="Phone number"
                    required
                  />
                </div>
                <div class="mb-4">
                  <label for="email" class="sr-only">Email address</label>
                  <input
                    type="email"
                    id="email"
                    name="email"
                    class="gap-2.5 self-stretch p-2.5 w-full rounded border border-solid border-zinc-400 max-md:max-w-full"
                    placeholder="Email address(optional)"
                  />
                </div>
              </div>
              <button
                type="submit"
                class="gap-2.5 self-stretch p-2.5 mt-6 max-w-full font-medium text-white bg-cyan-500 rounded-xl w-[221px] max-sm:mx-auto hover:bg-cyan-600 focus:outline-none focus:ring-2 focus:ring-cyan-500 focus:ring-offset-2"
              >
                Sign up
              </button>
            </form>
          </div>
          <div
            class="flex overflow-hidden flex-col justify-center py-px min-w-[240px] w-[300px]"
          >
            <img
              loading="lazy"
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/e82c2ebe0c20608c16409085e0280e5de4ead642dba5a1d581c314aef32f9b6c?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
              class="object-contain w-full aspect-[0.7] max-sm:mx-auto max-sm:max-w-[368px]"
              alt="Agent signup illustration"
            />
          </div>
        </div>
      </section>

      <footer
        class="flex overflow-hidden flex-col self-stretch px-16 py-8 mt-28 w-full bg-neutral-100 max-md:px-5 max-md:mt-10 max-md:max-w-full"
        role="contentinfo"
      >
        <div
          class="flex flex-wrap gap-10 justify-between items-start w-full max-md:max-w-full"
        >
          <nav
            class="flex flex-wrap gap-10 items-start text-2xl text-black min-w-[240px] max-md:max-w-full"
            aria-label="Footer navigation"
          >
            <div class="flex flex-col w-[179px]">
              <h3 class="font-bold">Your Account</h3>
              <a href="#support" class="mt-2">Contact Support</a>
              <a href="#agent" class="mt-2">Become an Agent</a>
              <a href="#help" class="mt-2">Help</a>
            </div>
            <div class="flex flex-col w-[187px]">
              <h3 class="font-bold">Xpenspay</h3>
              <a href="#about" class="mt-2">About</a>
              <a href="#mission" class="mt-2">Mission and Vision</a>
              <a href="#compliance" class="mt-2">Compliance</a>
              <a href="#partners" class="mt-2">Our Partners</a>
            </div>
            <div class="flex flex-col min-w-[240px] w-[293px]">
              <h3 class="font-bold">Safety Guidelines</h3>
              <a href="#protect" class="mt-2">Protecting your account</a>
              <a href="#money" class="mt-2">What happens to my money?</a>
              <a href="#faq" class="mt-2">FAQ</a>
            </div>
          </nav>
          <div class="flex flex-col min-w-[240px] w-[426px] max-md:max-w-full">
            <p class="text-base text-black max-md:max-w-full">
              Create an account and start getting the fastest speeds in Nigeria
            </p>
            <div class="flex gap-3.5 self-center mt-3.5 max-w-full w-[324px]">
              <img
                loading="lazy"
                src="https://cdn.builder.io/api/v1/image/assets/TEMP/fdd90d0ec841f5a45148c0f3014e3ee3dcaf912a04da03cb6702ad9efacfee8e?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
                class="object-contain shrink-0 max-w-full rounded-lg aspect-[3.37] w-[165px]"
                alt="App Store Download"
              />
              <img
                loading="lazy"
                src="https://cdn.builder.io/api/v1/image/assets/TEMP/4b7e7d82aa0c845b9a0d4d5ed62f70b77ae8c0695f46051c2d35aa0f06019db9?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
                class="object-contain shrink-0 max-w-full aspect-[2.98] w-[146px]"
                alt="Google Play Download"
              />
            </div>
          </div>
        </div>
        <div
          class="flex flex-col mt-16 max-w-full text-2xl text-right text-black w-[958px] max-md:mt-10"
        >
          <div
            class="flex flex-wrap gap-8 items-start w-full max-md:max-w-full max-sm:mx-auto"
          >
            <span class="font-bold max-sm:mr-auto">© 2024 Xpenspay</span>
            <a href="#cookie" class="max-sm:mr-auto">Cookie Policy</a>
            <a href="#terms" class="max-sm:mr-auto">Terms & Conditions</a>
            <a href="#privacy" class="max-sm:mr-auto">Privacy Policy</a>
            <button
              class="max-sm:mr-auto"
              aria-label="Cookie Settings"
              tabindex="0"
            >
              Cookie Settings
            </button>
          </div>
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/0affe808b6f7862ba411c28976a3e9ca595e55f5b86932fd1d32bdda5d2df5c4?placeholderIfAbsent=true&apiKey=c49e2462ddbf40d0944f306255d5e3e6"
            class="object-contain mt-7 max-w-full aspect-[4.1] w-[579px]"
            alt="Payment partners and certifications"
          />
        </div>
      </footer>
    </main>
  </div>
</template>
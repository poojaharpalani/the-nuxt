<div class="code1 flex justify-between px-56 py-28 dark:bg-gray-900">
  <div class="leftdiv">
    <div
      class="dark:bg-gray-900 text-white text-6xl font-[inter fallback] font-semibold py-2"
    >
      <h1 class="text-white">The power of</h1>
      <h1 class="text-[#00C16A]">Vue Components</h1>
    </div>

    <div class="text-white text-lg py-2">
      <p>
        We love Vue Single-File Components as much as you do. Simple,
        <br />
        intuitive and powerful, Nuxt lets you write Vue components in a
        <br />
        way that makes sense. Every repetitive task is automated, so you
        <br />
        can focus on writing your full-stack Vue application with
        <br />confidence.
      </p>
    </div>

    <div class="buttons py-2 flex gap-4">
      <button class="bg-white text-gray-900 h-9 rounded text-xl px-2"
        ><i class="bx bx-layout"></i> Learn about Views</button
      >
      <button
        class="dark:bg-gray-900 text-white border h-9 rounded text-xl px-2"
        ><span
          class="i-ph-app-window-duotone flex-shrink-0 h-5 w-5"
          aria-hidden="true"
        ></span>Hello World Example</button
      >
    </div>
  </div>
  <div class="rightdiv">
    <div class="codebox">
      <div
        class="topbar flex justify-between border solid border-gray-600 border-b-0 rounded-t-lg gap-16"
      >
        <div class="logo px-3 h-10 flex justify-center items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            class="icon"
            style=""
            width="1em"
            height="1em"
            viewBox="0 0 32 32"
            data-v-2115a7d5=""
            ><path
              fill="#41b883"
              d="M24.4 3.925H30l-14 24.15L2 3.925h10.71l3.29 5.6l3.22-5.6Z"
            ></path><path
              fill="#41b883"
              d="m2 3.925l14 24.15l14-24.15h-5.6L16 18.415L7.53 3.925Z"
            ></path><path
              fill="#35495e"
              d="M7.53 3.925L16 18.485l8.4-14.56h-5.18L16 9.525l-3.29-5.6Z"
            ></path></svg
          >
          <span class="text-gray-700 dark:text-gray-200 text-sm/6">app.vue</span
          >
        </div>
        <button class="copy px-3"
          ><i class="bx bx-copy text-gray-600"></i></button
        >
      </div>
      <div
        class="maincode border solid border-gray-600 bg-gray-800 rounded-b-lg"
      >
        <pre
          class="language-vue shiki shiki-themes material-theme-lighter material-theme-lighter material-theme-palenight"
          style="">
          <code
            ><span class="line" line="1"
              ><span style="color:#39ADB5">&lt;</span><span
                style="color:#E53935;">script</span
              ><span style="color:#9C3EDA"> setup</span><span
                style="color:#39ADB5"
                >&gt;
        </span></span
            >
        <span class="line" line="2"
              ><span style="color:#6182B8">useSeoMeta</span><span
                style="color:#90A4AE">(</span
              ><span style="color:#39ADB5">&#123;</span>
              </span><span class="line" line="3"
              ><span style="color:#E53935;">  title</span><span
                style="color:#39ADB5">:</span
              ><span style="color:#39ADB5"> '</span><span style="color:#91B859"
                >Meet Nuxt</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >,
        </span></span
            ><span class="line" line="4"
              ><span style="color:#E53935;">  description</span><span
                style="color:#39ADB5">:</span
              ><span style="color:#39ADB5"> '</span><span style="color:#91B859"
                >The Intuitive Vue Framework.</span
              ><span style="color:#39ADB5"
                >'
        </span></span
            ><span class="line" line="5"
              ><span style="color:#39ADB5">&#125;</span><span
                style="color:#90A4AE"
                >)
        </span></span
            ><span class="line" line="6"
              ><span style="color:#39ADB5">&lt;/</span><span
                style="color:#E53935;">script</span
              ><span style="color:#39ADB5"
                >&gt;
        </span></span
            ><span class="line" line="7"
              ><span emptylineplaceholder="true"></span></span
            ><span class="line" line="8"
              ><span style="color:#39ADB5">&lt;</span><span
                style="color:#E53935;">template</span
              ><span style="color:#39ADB5"
                >&gt;
        </span></span
            ><span class="line" line="9"
              ><span style="color:#39ADB5">  &lt;</span><span
                style="color:#E53935;">div</span
              ><span style="color:#9C3EDA"> id</span><span style="color:#39ADB5"
                >=</span
              ><span style="color:#39ADB5">"</span><span style="color:#91B859"
                >app</span
              ><span style="color:#39ADB5">"</span><span style="color:#39ADB5"
                >&gt;
        </span></span
            ><span class="line" line="10"
              ><span style="color:#39ADB5">    &lt;</span><span
                style="color:#E53935;">AppHeader</span
              ><span style="color:#39ADB5"> /&gt;
        </span></span
            ><span class="line" line="11"
              ><span style="color:#39ADB5">    &lt;</span><span
                style="color:#E53935;">NuxtPage</span
              ><span style="color:#39ADB5"> /&gt;
        </span></span
            ><span class="line" line="12"
              ><span style="color:#39ADB5">    &lt;</span><span
                style="color:#E53935;">AppFooter</span
              ><span style="color:#39ADB5"> /&gt;
        </span></span
            ><span class="line" line="13"
              ><span style="color:#39ADB5">  &lt;/</span><span
                style="color:#E53935;">div</span
              ><span style="color:#39ADB5"
                >&gt;
        </span></span
            ><span class="line" line="14"
              ><span style="color:#39ADB5">&lt;/</span><span
                style="color:#E53935;">template</span
              ><span style="color:#39ADB5"
                >&gt;
        </span></span
            ><span class="line" line="15"
              ><span emptylineplaceholder="true"></span></span
            ><span class="line" line="16"
              ><span style="color:#39ADB5">&lt;</span><span
                style="color:#E53935;">style</span
              ><span style="color:#39ADB5"
                >&gt;
        </span></span
            ><span class="line" line="17"
              ><span style="color:#39ADB5">#</span><span style="color:#F76D47"
                >app</span
              ><span style="color:#39ADB5">&#123</span></span
            ><span class="line" line="18"
              ><span style="color:#8796B0">  background-color</span><span
                style="color:#39ADB5">:</span
              ><span style="color:#39ADB5"> #</span><span style="color:#90A4AE"
                >020420</span
              ><span style="color:#39ADB5"
                >;
        </span></span
            ><span class="line" line="19"
              ><span style="color:#8796B0">  color</span><span
                style="color:#39ADB5">:</span
              ><span style="color:#39ADB5"> #</span><span style="color:#90A4AE"
                >00DC82</span
              ><span style="color:#39ADB5"
                >;
        </span></span
            ><span class="line" line="20"
              ><span style="color:#39ADB5"
                >&#125
        </span></span
            ><span class="line" line="21"
              ><span style="color:#39ADB5">&lt;/</span><span
                style="color:#E53935;">style</span
              ><span style="color:#39ADB5"
                >&gt;
        </span></span
            ></code
          ><!--]--></pre>
      </div>
    </div>
  </div>
</div>
<div class="code2 flex justify-between px-28 py-56 dark:bg-gray-900 gap-16">
  <div class="lefttdiv">
    <div class="codebox">
      <div
        class="topbar flex justify-between border solid border-gray-600 border-b-0 rounded-t-lg"
      >
        <div class="logo px-3 h-10 flex justify-center items-center gap-3">
          <div
            class="topbutton1 flex justify-center items-center border border-gray-700 rounded bg-gray-600 px-6"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              role="img"
              class="icon"
              style=""
              width="1em"
              height="1em"
              viewBox="0 0 32 32"
              data-v-2115a7d5=""
              ><path
                fill="#00DC82"
                d="M17.708 25h10.409c.33 0 .655-.088.942-.254a1.9 1.9 0 0 0 .689-.696a1.91 1.91 0 0 0 0-1.9L22.756 9.936a1.87 1.87 0 0 0-3.261 0l-1.788 3.125l-3.494-6.111a1.871 1.871 0 0 0-3.262 0l-8.7 15.2a1.91 1.91 0 0 0 .69 2.595c.286.167.61.255.941.255h6.534c2.589 0 4.498-1.147 5.811-3.385l3.19-5.572l1.708-2.982l5.127 8.957h-6.835zm-7.398-2.985l-4.56-.001l6.836-11.942l3.41 5.97l-2.283 3.992c-.873 1.452-1.864 1.981-3.403 1.981"
              ></path></svg
            >
            <span class="text-gray-700 dark:text-gray-200 text-sm/6"
              >nuxt.config.ts</span
            >
          </div>
          <div class="topbutton2 flex justify-center items-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              role="img"
              class="icon"
              style=""
              width="1em"
              height="1em"
              viewBox="0 0 32 32"
              data-v-2115a7d5=""
              ><path
                fill="#41b883"
                d="M24.4 3.925H30l-14 24.15L2 3.925h10.71l3.29 5.6l3.22-5.6Z"
              ></path><path
                fill="#41b883"
                d="m2 3.925l14 24.15l14-24.15h-5.6L16 18.415L7.53 3.925Z"
              ></path><path
                fill="#35495e"
                d="M7.53 3.925L16 18.485l8.4-14.56h-5.18L16 9.525l-3.29-5.6Z"
              ></path></svg
            >
            <span class="text-gray-700 dark:text-gray-200 text-sm/6"
              >app.vue</span
            >
          </div>
        </div>
        <button class="copy px-3"
          ><i class="bx bx-copy text-gray-600"></i></button
        >
      </div>
      <div
        class="maincode border solid border-gray-600 bg-gray-800 rounded-b-lg"
      >
        <pre
          class="language-ts shiki shiki-themes material-theme-lighter material-theme-lighter material-theme-palenight"><code
            ><span class="line" line="1"
              ><span style="color:#39ADB5">export</span><span
                style="color:#39ADB5"> default</span
              ><span style="color:#6182B8"> defineNuxtConfig</span><span
                style="color:#90A4AE">(</span
              ><span style="color:#39ADB5"
                >&#123
      </span></span
            ><span class="line" line="2"
              ><span style="color:#E53935">  routeRules</span><span
                style="color:#39ADB5">:</span
              ><span style="color:#39ADB5"> &#123
      </span></span
            ><span class="line" line="3"
              ><span
                style="color:#B0BEC5 font-style: italic;">    // Homepage pre-rendered at build time
      </span></span
            ><span class="line" line="4"
              ><span style="color:#39ADB5">    '</span><span
                style="color:#E53935">/</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >:</span
              ><span style="color:#39ADB5"> &#123</span><span
                style="color:#E53935"> prerender</span
              ><span style="color:#39ADB5">:</span><span
                style="color:#FF5370"> true</span
              ><span style="color:#39ADB5"> &#125,
      </span></span
            ><span class="line" line="5"
              ><span
                style="color:#90A4AE font-style: italic;">    // Product page generated on-demand, revalidates in background
      </span></span
            ><span class="line" line="6"
              ><span style="color:#39ADB5">    '</span><span
                style="color:#E53935">/products/**</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >:</span
              ><span style="color:#39ADB5"> &#123</span><span
                style="color:#E53935"> swr</span
              ><span style="color:#39ADB5">:</span><span
                style="color:#FF5370"> true</span
              ><span style="color:#39ADB5"> &#125,
      </span></span
            ><span class="line" line="7"
              ><span
                style="color:#90A4AE font-style: italic;">    // Blog post generated on-demand once until next deploy
      </span></span
            ><span class="line" line="8"
              ><span style="color:#39ADB5">    '</span><span
                style="color:#E53935">/blog/**</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >:</span
              ><span style="color:#39ADB5"> &#123</span><span
                style="color:#E53935"> isr</span
              ><span style="color:#39ADB5">:</span><span
                style="color:#FF5370"> true</span
              ><span style="color:#39ADB5"> &#125,
      </span></span
            ><span class="line" line="9"
              ><span
                style="color:#90A4AE font-style: italic;">    // Admin dashboard renders only on client-side
      </span></span
            ><span class="line" line="10"
              ><span style="color:#39ADB5">    '</span><span
                style="color:#E53935">/admin/**</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >:</span
              ><span style="color:#39ADB5"> &#123</span><span
                style="color:#E53935"> ssr</span
              ><span style="color:#39ADB5">:</span><span
                style="color:#FF5370"> false</span
              ><span style="color:#39ADB5"> },
      </span></span
            ><span class="line" line="11"
              ><span
                style="color:#90A4AE font-style: italic;">    // Add cors headers on API routes
      </span></span
            ><span class="line" line="12"
              ><span style="color:#39ADB5">    '</span><span
                style="color:#E53935">/api/**</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >:</span
              ><span style="color:#39ADB5"> &#123</span><span
                style="color:#E53935"> cors</span
              ><span style="color:#39ADB5">:</span><span
                style="color:#FF5370"> true</span
              ><span style="color:#39ADB5"> &#125,
      </span></span
            ><span class="line" line="13"
              ><span
                style="color:#90A4AE font-style: italic;">    // Redirects legacy urls
      </span></span
            ><span class="line" line="14"
              ><span style="color:#39ADB5">    '</span><span
                style="color:#E53935">/old-page</span
              ><span style="color:#39ADB5">'</span><span style="color:#39ADB5"
                >:</span
              ><span style="color:#39ADB5"> &#123</span><span
                style="color:#E53935"> redirect</span
              ><span style="color:#39ADB5">:</span><span
                style="color:#39ADB5"> '</span
              ><span style="color:#91B859">/new-page</span><span
                style="color:#39ADB5">'</span
              ><span style="color:#39ADB5"> &#125
      </span></span
            ><span class="line" line="15"
              ><span style="color:#39ADB5">  &#125
      </span></span
            ><span class="line" line="16"
              ><span style="color:#39ADB5">&#125</span><span
                style="color:#90A4AE"
                >)
      </span></span
            ></code
          ></pre>
      </div>
    </div>
  </div>
  <div class="righttdiv">
    <div
      class="dark:bg-gray-900 text-white text-6xl font-[inter fallback] font-semibold py-2"
    >
      <h1 class="text-white">Static or Dynamic,</h1>
      <h1 class="text-[#00C16A]">the choice is yours</h1>
    </div>

    <div class="text-white text-lg py-2">
      <p>
        Decide what rendering strategy you need at the route level. By
        <br />
        leveraging the hybrid rendering, you can get the best of both
        <br />
        worlds: the performance of a static site and the interactivity of a can focus
        <br />dynamic one.
      </p>
    </div>

    <div class="buttons py-2 flex gap-4 justify-between">
      <button class="bg-white text-gray-900 h-9 rounded text-xl w-1/2"
        ><i class="bx bx-layout"></i> Learn about Hybrid Rendering</button
      >
      <button
        class="dark:bg-gray-900 text-white border h-9 rounded text-xl px-2 w-1/2"
        ><span
          class="i-ph-newspaper-duotone flex-shrink-0 h-5 w-5"
          aria-hidden="true"
        >
          Nuxt on the edge</span
        ></button
      >
    </div>
  </div>
</div>

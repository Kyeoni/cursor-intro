<template>
  <div class="card-group not-prose grid gap-x-4 sm:grid-cols-3"><a
      class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
      href="/chat/agent">
      <div class="px-6 py-5 relative" data-component-part="card-content-container">
        <div id="card-link-arrow-icon"
          class="absolute text-gray-400 dark:text-gray-500 group-hover:text-primary dark:group-hover:text-primary-light top-5 right-5 hidden">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
            class="lucide lucide-arrow-up-right w-4 h-4">
            <path d="M7 7h10v10"></path>
            <path d="M7 17 17 7"></path>
          </svg>
        </div>
        <div class="h-6 w-6 fill-gray-800 dark:fill-gray-100 text-gray-800 dark:text-gray-100"
          data-component-part="card-icon"><svg class="h-6 w-6 bg-primary dark:bg-primary-light"
            style="mask-image: url(&quot;https://mintlify.b-cdn.net/v6.6.0/regular/infinity.svg&quot;); mask-repeat: no-repeat; mask-position: center center;"></svg>
        </div>
        <div>
          <h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white mt-4" contenteditable="false"
            data-component-part="card-title">
            <font style="vertical-align: inherit;">
              <font style="vertical-align: inherit;">代理模式/Agent</font>
            </font>
          </h2>
          <div class="prose mt-1 font-normal text-sm leading-6 text-gray-600 dark:text-gray-400"
            data-component-part="card-content">
            <p>
              <font style="vertical-align: inherit;">
                <font style="vertical-align: inherit;">允许 Cursor</font>
              </font><strong>
                <font style="vertical-align: inherit;">
                  <font style="vertical-align: inherit;">自主学习</font>
                </font>
              </strong>
              <font style="vertical-align: inherit;">
                <font style="vertical-align: inherit;">您的代码库，并代表</font>
                <font style="vertical-align: inherit;">您进行</font>
              </font><strong>
                <font style="vertical-align: inherit;">
                  <font style="vertical-align: inherit;">代码库范围的更改</font>
                </font>
              </strong>
              <font style="vertical-align: inherit;"></font>
            </p>
          </div>
        </div>
      </div>
    </a><a
      class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
      href="/chat/ask">
      <div class="px-6 py-5 relative" data-component-part="card-content-container">
        <div id="card-link-arrow-icon"
          class="absolute text-gray-400 dark:text-gray-500 group-hover:text-primary dark:group-hover:text-primary-light top-5 right-5 hidden">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
            class="lucide lucide-arrow-up-right w-4 h-4">
            <path d="M7 7h10v10"></path>
            <path d="M7 17 17 7"></path>
          </svg>
        </div>
        <div class="h-6 w-6 fill-gray-800 dark:fill-gray-100 text-gray-800 dark:text-gray-100"
          data-component-part="card-icon"><svg class="h-6 w-6 bg-primary dark:bg-primary-light"
            style="mask-image: url(&quot;https://mintlify.b-cdn.net/v6.6.0/regular/comment.svg&quot;); mask-repeat: no-repeat; mask-position: center center;"></svg>
        </div>
        <div>
          <h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white mt-4" contenteditable="false"
            data-component-part="card-title">
            <font style="vertical-align: inherit;">
              <font style="vertical-align: inherit;">询问模式/Ask</font>
            </font>
          </h2>
          <div class="prose mt-1 font-normal text-sm leading-6 text-gray-600 dark:text-gray-400"
            data-component-part="card-content">
            <p>
              <font style="vertical-align: inherit;">
                <font style="vertical-align: inherit;">获取有关代码库的解释和答案，并使用 AI 规划功能</font>
              </font>
            </p>
          </div>
        </div>
      </div>
    </a><a
      class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
      href="/chat/manual">
      <div class="px-6 py-5 relative" data-component-part="card-content-container">
        <div id="card-link-arrow-icon"
          class="absolute text-gray-400 dark:text-gray-500 group-hover:text-primary dark:group-hover:text-primary-light top-5 right-5 hidden">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
            class="lucide lucide-arrow-up-right w-4 h-4">
            <path d="M7 7h10v10"></path>
            <path d="M7 17 17 7"></path>
          </svg>
        </div>
        <div class="h-6 w-6 fill-gray-800 dark:fill-gray-100 text-gray-800 dark:text-gray-100"
          data-component-part="card-icon"><svg class="h-6 w-6 bg-primary dark:bg-primary-light"
            style="mask-image: url(&quot;https://mintlify.b-cdn.net/v6.6.0/regular/crosshairs.svg&quot;); mask-repeat: no-repeat; mask-position: center center;"></svg>
        </div>
        <div>
          <h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white mt-4" contenteditable="false"
            data-component-part="card-title">
            <font style="vertical-align: inherit;">
              <font style="vertical-align: inherit;">手动模式/Manual</font>
            </font>
          </h2>
          <div class="prose mt-1 font-normal text-sm leading-6 text-gray-600 dark:text-gray-400"
            data-component-part="card-content">
            <p>
              <font style="vertical-align: inherit;">
                <font style="vertical-align: inherit;">仅使用您提供的上下文进行有针对性的编辑</font>
              </font>
            </p>
          </div>
        </div>
      </div>
    </a></div>
  <div class="card-group not-prose grid gap-x-4 sm:grid-cols-1"><a
      class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
      href="/chat/custom-modes">
      <div class="px-6 py-5 relative flex items-center gap-x-3" data-component-part="card-content-container">
        <div id="card-link-arrow-icon"
          class="absolute text-gray-400 dark:text-gray-500 group-hover:text-primary dark:group-hover:text-primary-light top-5 right-5 hidden">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
            class="lucide lucide-arrow-up-right w-4 h-4">
            <path d="M7 7h10v10"></path>
            <path d="M7 17 17 7"></path>
          </svg>
        </div>
        <div class="h-6 w-6 fill-gray-800 dark:fill-gray-100 text-gray-800 dark:text-gray-100"
          data-component-part="card-icon"><svg class="h-6 w-6 bg-primary dark:bg-primary-light"
            style="mask-image: url(&quot;https://mintlify.b-cdn.net/v6.6.0/regular/crosshairs.svg&quot;); mask-repeat: no-repeat; mask-position: center center;"></svg>
        </div>
        <div>
          <h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white" contenteditable="false"
            data-component-part="card-title">
            <font style="vertical-align: inherit;">
              <font style="vertical-align: inherit;">自定义模式/Custom（Beta）</font>
            </font>
          </h2>
          <div class="prose font-normal text-sm text-gray-600 dark:text-gray-400 leading-6 mt-0"
            data-component-part="card-content">
            <p>
              <font style="vertical-align: inherit;">
                <font style="vertical-align: inherit;">创建自定义模式以适合您的特定工作流程</font>
              </font>
            </p>
          </div>
        </div>
      </div>
    </a></div>
</template>
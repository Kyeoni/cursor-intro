<!--
 * @Description: 
 * @Author: Kyeoni hujr
 * @Date: 2025-05-27 16:03:04
 * @LastEditors: Kyeoni hujr
 * @LastEditTime: 2025-05-28 17:19:48
-->
<template>
	<!-- <div class="flex items-center">
		<div>Tab：按下Tab可实现智能代码补全</div>
		<carbon:play class="inline-block ml-2 cursor-pointer text-blue-500 hover:text-blue-700" @click="goToSlide" />
	</div> -->
	<div class="card-group not-prose grid gap-x-4 sm:grid-cols-3"><a
			class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
			href="https://docs.cursor.com/tab/overview">
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
						style="mask-image: url(&quot;https://mintlify.b-cdn.net/v6.6.0/regular/arrow-right.svg&quot;); mask-repeat: no-repeat; mask-position: center center;"></svg>
				</div>
				<div>
					<h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white mt-4"
						contenteditable="false" data-component-part="card-title">
						<font style="vertical-align: inherit;">
							<font style="vertical-align: inherit;">Tab</font>
						</font>
					</h2>
					<div class="prose mt-1 font-normal text-sm leading-6 text-gray-600 dark:text-gray-400"
						data-component-part="card-content">
						<div class="mint-text-sm">
							<p>
								<font style="vertical-align: inherit;">
									<font style="vertical-align: inherit;">Tab 可以预测下一系列编辑。
									</font>
								</font>
							</p>
						</div>
					</div>
				</div>
			</div>
		</a><a
			class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
			href="https://docs.cursor.com/chat/overview">
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
					<h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white mt-4"
						contenteditable="false" data-component-part="card-title">
						<font style="vertical-align: inherit;">
							<font style="vertical-align: inherit;">Chat/Agent</font>
						</font>
					</h2>
					<div class="prose mt-1 font-normal text-sm leading-6 text-gray-600 dark:text-gray-400"
						data-component-part="card-content">
						<div class="mint-text-sm">
							<p>
								<font style="vertical-align: inherit;">
									<font style="vertical-align: inherit;">AI 结对程序员，可处理复杂的代码修改。使用上下文控制和自动修复功能进行大规模编辑。
									</font>
								</font>
							</p>
						</div>
					</div>
				</div>
			</div>
		</a><a
			class="card block font-normal group relative my-2 ring-2 ring-transparent rounded-2xl bg-white dark:bg-background-dark border border-gray-950/10 dark:border-white/10 overflow-hidden w-full cursor-pointer hover:!border-primary dark:hover:!border-primary-light"
			href="https://docs.cursor.com/cmdk/overview">
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
						style="mask-image: url(&quot;https://mintlify.b-cdn.net/v6.6.0/regular/code.svg&quot;); mask-repeat: no-repeat; mask-position: center center;"></svg>
				</div>
				<div>
					<h2 class="not-prose font-semibold text-base text-gray-800 dark:text-white mt-4"
						contenteditable="false" data-component-part="card-title">
						<font style="vertical-align: inherit;">
							<font style="vertical-align: inherit;">Cmd-K</font>
						</font>
					</h2>
					<div class="prose mt-1 font-normal text-sm leading-6 text-gray-600 dark:text-gray-400"
						data-component-part="card-content">
						<div class="mint-text-sm">
							<p>
								<font style="vertical-align: inherit;">
									<font style="vertical-align: inherit;">快速内联代码编辑和生成。适合在不中断流程的情况下进行精确更改。</font>
								</font>
							</p>
						</div>
					</div>
				</div>
			</div>
		</a></div>
</template>

<template>
    <div class="grid grid-cols-2 gap-8 mt-10 mb-6">
        <!-- 左栏 - 前3个步骤 -->
        <div role="list" class="steps ml-3.5">
            <div role="listitem" class="step relative flex items-start pb-2">
                <div class="absolute w-px h-[calc(100%-2.75rem)] top-[2.75rem] bg-gray-200/70 dark:bg-white/10"
                    contenteditable="false"></div>
                <div class="absolute ml-[-14px] py-2" data-component-part="step-number" contenteditable="false">
                    <div
                        class="w-7 h-7 shrink-0 rounded-lg bg-gray-100 dark:text-white dark:bg-[#26292E] text-sm text-gray-800 font-semibold flex items-center justify-center">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">1</span>
                        </span>
                    </div>
                </div>
                <div class="w-full overflow-hidden pl-12 pr-px">
                    <p class="mt-2 font-semibold prose dark:prose-invert text-gray-900 dark:text-gray-200"
                        contenteditable="false" data-component-part="step-title">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">理解需求</span>
                        </span>
                    </p>
                    <div data-component-part="step-content">
                        <p>
                            <span style="vertical-align: inherit;">
                                <span style="vertical-align: inherit;">智能代理首先分析用户的需求和代码库结构，深入理解任务目标和实现方向。</span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
            <div role="listitem" class="step relative flex items-start pb-2">
                <div class="absolute w-px h-[calc(100%-2.75rem)] top-[2.75rem] bg-gray-200/70 dark:bg-white/10"
                    contenteditable="false"></div>
                <div class="absolute ml-[-14px] py-2" data-component-part="step-number" contenteditable="false">
                    <div
                        class="w-7 h-7 shrink-0 rounded-lg bg-gray-100 dark:text-white dark:bg-[#26292E] text-sm text-gray-800 font-semibold flex items-center justify-center">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">2</span>
                        </span>
                    </div>
                </div>
                <div class="w-full overflow-hidden pl-12 pr-px">
                    <p class="mt-2 font-semibold prose dark:prose-invert text-gray-900 dark:text-gray-200"
                        contenteditable="false" data-component-part="step-title">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">分析代码</span>
                        </span>
                    </p>
                    <div data-component-part="step-content">
                        <p>
                            <span style="vertical-align: inherit;">
                                <span style="vertical-align: inherit;">智能搜索代码库、项目文档和相关资料，全面了解项目现状和技术架构。</span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
            <div role="listitem" class="step relative flex items-start pb-2">
                <div class="absolute w-px h-[calc(100%-2.75rem)] top-[2.75rem] bg-transparent bg-gradient-to-b from-gray-200 dark:from-white/10 via-80% to-transparent"
                    contenteditable="false"></div>
                <div class="absolute ml-[-14px] py-2" data-component-part="step-number" contenteditable="false">
                    <div
                        class="w-7 h-7 shrink-0 rounded-lg bg-gray-100 dark:text-white dark:bg-[#26292E] text-sm text-gray-800 font-semibold flex items-center justify-center">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">3</span>
                        </span>
                    </div>
                </div>
                <div class="w-full overflow-hidden pl-12 pr-px">
                    <p class="mt-2 font-semibold prose dark:prose-invert text-gray-900 dark:text-gray-200"
                        contenteditable="false" data-component-part="step-title">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">制定方案</span>
                        </span>
                    </p>
                    <div data-component-part="step-content">
                        <p>
                            <span style="vertical-align: inherit;">
                                <span style="vertical-align: inherit;">根据分析结果，将复杂任务拆解为可执行的步骤，制定详细的实施方案。</span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <!-- 右栏 - 后3个步骤 -->
        <div role="list" class="steps ml-3.5">
            <div role="listitem" class="step relative flex items-start pb-2">
                <div class="absolute w-px h-[calc(100%-2.75rem)] top-[2.75rem] bg-gray-200/70 dark:bg-white/10"
                    contenteditable="false"></div>
                <div class="absolute ml-[-14px] py-2" data-component-part="step-number" contenteditable="false">
                    <div
                        class="w-7 h-7 shrink-0 rounded-lg bg-gray-100 dark:text-white dark:bg-[#26292E] text-sm text-gray-800 font-semibold flex items-center justify-center">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">4</span>
                        </span>
                    </div>
                </div>
                <div class="w-full overflow-hidden pl-12 pr-px">
                    <p class="mt-2 font-semibold prose dark:prose-invert text-gray-900 dark:text-gray-200"
                        contenteditable="false" data-component-part="step-title">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">实施修改</span>
                        </span>
                    </p>
                    <div data-component-part="step-content">
                        <p>
                            <span style="vertical-align: inherit;">
                                <span style="vertical-align: inherit;">按照方案对代码进行修改，同时可能推荐安装新依赖、执行命令或提供Cursor外的操作指导。
                                </span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
            <div role="listitem" class="step relative flex items-start pb-2">
                <div class="absolute w-px h-[calc(100%-2.75rem)] top-[2.75rem] bg-gray-200/70 dark:bg-white/10"
                    contenteditable="false"></div>
                <div class="absolute ml-[-14px] py-2" data-component-part="step-number" contenteditable="false">
                    <div
                        class="w-7 h-7 shrink-0 rounded-lg bg-gray-100 dark:text-white dark:bg-[#26292E] text-sm text-gray-800 font-semibold flex items-center justify-center">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">5</span>
                        </span>
                    </div>
                </div>
                <div class="w-full overflow-hidden pl-12 pr-px">
                    <p class="mt-2 font-semibold prose dark:prose-invert text-gray-900 dark:text-gray-200"
                        contenteditable="false" data-component-part="step-title">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">检验效果</span>
                        </span>
                    </p>
                    <div data-component-part="step-content">
                        <p>
                            <span style="vertical-align: inherit;">
                                <span style="vertical-align: inherit;">应用修改后，自动检查代码是否正确运行，发现语法错误或问题时会主动修复。</span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
            <div role="listitem" class="step relative flex items-start pb-2">
                <div class="absolute w-px h-[calc(100%-2.75rem)] top-[2.75rem] bg-transparent bg-gradient-to-b from-gray-200 dark:from-white/10 via-80% to-transparent"
                    contenteditable="false"></div>
                <div class="absolute ml-[-14px] py-2" data-component-part="step-number" contenteditable="false">
                    <div
                        class="w-7 h-7 shrink-0 rounded-lg bg-gray-100 dark:text-white dark:bg-[#26292E] text-sm text-gray-800 font-semibold flex items-center justify-center">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">6</span>
                        </span>
                    </div>
                </div>
                <div class="w-full overflow-hidden pl-12 pr-px">
                    <p class="mt-2 font-semibold prose dark:prose-invert text-gray-900 dark:text-gray-200"
                        contenteditable="false" data-component-part="step-title">
                        <span style="vertical-align: inherit;">
                            <span style="vertical-align: inherit;">完成总结</span>
                        </span>
                    </p>
                    <div data-component-part="step-content">
                        <p>
                            <span style="vertical-align: inherit;">
                                <span style="vertical-align: inherit;">确认所有修改无误后，向用户汇报完成情况，总结本次任务的主要改动。</span>
                            </span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
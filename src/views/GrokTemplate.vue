<script lang="ts">
</script>

<template>
    <div class="mb-16 bg-[#F8F8F8] md:max-w-screen-md lg:max-w-screen-lg md:mx-auto" data-testid="course-group">
        <p class="font-semibold text-2xl mb-4" data-testid="course-group-label" role="heading">All</p>
        <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Assigned
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/python-green.svg"><a
                        class="mt-3" href="/course/python-for-beginners/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Python for Beginners</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to code with Python! Perfect for beginners
                        of all ages.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/python-for-beginners/">View details</a><a href="/learn/python-for-beginners/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/R9KksuNJa6qEei329FUorH/InformationPrivacySecurityx2.svg"><a
                        class="mt-3" href="/course/cyber-hs-infosec-v2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Information Privacy and
                            Security - Secondary</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Are you sharing too much information online?</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-6</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-hs-infosec-v2/">View details</a><a href="/learn/cyber-hs-infosec-v2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/html-css-green.svg"><a
                        class="mt-3" href="/course/intro-html-css-starter/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Express HTML/CSS</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">A short course on the basics of HTML and CSS.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">HTML/CSS</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/intro-html-css-starter/">View details</a><a href="/learn/intro-html-css-starter/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/html-css-green.svg"><a
                        class="mt-3" href="/course/intro-html-css-beginners-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Beginners 1 HTML/CSS</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Continue the HTML/CSS journey, with the first of
                        our two-part course for beginners!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">HTML/CSS</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/intro-html-css-beginners-1/">View details</a><a
                        href="/learn/intro-html-css-beginners-1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-monster.svg"><a
                        class="mt-3" href="/csedweek/hoc-monster-maker-interactive/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Monster Maker - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming and create your own
                        monsters!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-monster-maker-interactive/">View details</a><a
                        href="/learn/hoc-monster-maker-interactive/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-34-scratch-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Get Started - Scratch</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to use Scratch with step by step
                        instructions.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Scratch</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-34-scratch-1/">View details</a><a href="/learn/aca-dt-34-scratch-1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/NNxTW9DJ7rW8sBVjfCT53f/cyber_pursuit_transparent.png"><a
                        class="mt-3" href="/csedweek/cyber-hunt/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Cyber Hunt</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Warm up with these short cyber activities!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>11</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/cyber-hunt/">View details</a><a href="/learn/cyber-hunt/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/microbit-green.svg"><a
                        class="mt-3" href="/course/microbit-crash-course/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Beginners micro:bit - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">A fast-paced introduction to programming with the
                        BBC micro:bit.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/microbit-crash-course/">View details</a><a href="/learn/microbit-crash-course/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Assigned
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-78-py-turtle/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Beginners Turtle - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Write code to control the Turtle and draw
                        fantastic pictures!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-78-py-turtle/">View details</a><a href="/learn/aca-dt-78-py-turtle/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-56-bk-turtle/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Beginners Turtle - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Write code to control a turtle and draw fantastic
                        pictures!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-56-bk-turtle/">View details</a><a href="/learn/aca-dt-56-bk-turtle/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/python-yellow.svg"><a
                        class="mt-3" href="/course/intro-python-2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Introduction to Programming 2 -
                            Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Finished Python for Beginners and want more?</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/intro-python-2/">View details</a><a href="/learn/intro-python-2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/Nv2pzwM3FCE47eZmXuahXe/Cyberhackerphone.svg"><a
                        class="mt-3" href="/csedweek/hoc-cyber-security/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Defence Against the Dark Hats
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about cyber security and how to stay safe
                        online!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-cyber-security/">View details</a><a href="/learn/hoc-cyber-security/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/rXHgFVcyKTdCf2LAEcsLgH/CyberPrimaryx2.svg"><a
                        class="mt-3" href="/course/cyber-ps-infosec/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Information Privacy and
                            Security - Primary</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Take on the role of a cyber security expert and
                        get sleuthing, to learn about cyber security!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-ps-infosec/">View details</a><a href="/learn/cyber-ps-infosec/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-34-scratch-2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Get Moving - Scratch</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to move sprites around the stage using
                        Scratch!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Scratch</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-34-scratch-2/">View details</a><a href="/learn/aca-dt-34-scratch-2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/monsters-1.svg"><a
                        class="mt-3" href="/course/monsters-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Monster Maker 1</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Create your own colourful critters with code!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/monsters-1/">View details</a><a href="/learn/monsters-1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/html-css-green.svg"><a
                        class="mt-3" href="/course/intro-html-css-beginners-2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Beginners 2 HTML/CSS</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Continue learning the basics of HTML and CSS!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">HTML/CSS</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>3-6</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/intro-html-css-beginners-2/">View details</a><a
                        href="/learn/intro-html-css-beginners-2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-34-scratch-3/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Get Interactive - Scratch</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to use Scratch with step by step
                        instructions.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Scratch</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-34-scratch-3/">View details</a><a href="/learn/aca-dt-34-scratch-3/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/NxQRYfXHH4iSqLrQXNsb6P/GDB-433SpottheScamIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-5/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Spot The
                            Scam</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Become a savvy digital detective!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-5/">View details</a><a href="/learn/digital-exploration-5/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/eZPWsTW9qQrnXU7TS5Y2Hf/cyberstamp-02.svg"><a
                        class="mt-3" href="/course/cybermarvel/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Cybermarvel</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">An introduction to cyber security for students in
                        Years 3 to 6!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-6</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cybermarvel/">View details</a><a href="/learn/cybermarvel/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/4RUHY2cGCav9ccgiNZnGU/coursebadgedataanalytics.svg"><a
                        class="mt-3" href="/course/dt-applied-data-analytics/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Data Analytics</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Data Analytics gives you the power to interpret,
                        manipulate and draw meaningful insights using real-world data sets.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/dt-applied-data-analytics/">View details</a><a
                        href="/learn/dt-applied-data-analytics/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/monsters-2.svg"><a
                        class="mt-3" href="/course/monsters-2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Monster Maker 2</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Write programs that ask questions and make
                        decisions!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/monsters-2/">View details</a><a href="/learn/monsters-2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-34-scratch-4/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Get Looping - Scratch</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to use Scratch with step by step
                        instructions.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Scratch</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-34-scratch-4/">View details</a><a href="/learn/aca-dt-34-scratch-4/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-virtual-pet-blockly.svg"><a
                        class="mt-3" href="/csedweek/hoc-virtual-pet-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Virtual Pet micro:bit - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming with the BBC
                        micro:bit.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-virtual-pet-blockly/">View details</a><a
                        href="/learn/hoc-virtual-pet-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/databases-green@2x.png"><a
                        class="mt-3" href="/course/intro-sql-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Beginners Databases - SQL</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">An introduction to databases and Structured Query
                        Language (SQL).</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">SQL</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/intro-sql-1/">View details</a><a href="/learn/intro-sql-1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-green.svg"><a
                        class="mt-3" href="/gym/python-playground/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Workspace for your own Python programs.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>5</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/python-playground/">View details</a><a href="/learn/python-playground/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        Practice</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Assigned
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-green.svg"><a
                        class="mt-3" href="/csedweek/hoc-flags/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Flags - Python Turtle</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-flags/">View details</a><a href="/learn/hoc-flags/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/wvF3kuyU52tRHjqyrCCdTJ/coursebadge.svg"><a
                        class="mt-3" href="/course/dt-applied-design-thinking/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Design Thinking</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Design Thinking gives you the tools to solve any
                        problem with creativity and confidence!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/dt-applied-design-thinking/">View details</a><a
                        href="/learn/dt-applied-design-thinking/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/cpAZbAFcwjwPAzFR645AmS/UXUICourseicon.svg"><a
                        class="mt-3" href="/course/dt-applied-ui-ux/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">UX/UI Design</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about UX/UI prototyping and design, and
                        create your own mobile interface!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/dt-applied-ui-ux/">View details</a><a href="/learn/dt-applied-ui-ux/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-mini-34-bk-wombot/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Wombot - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Write code to help Wombot move, turn and find
                        delicious carrots to eat!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-mini-34-bk-wombot/">View details</a><a
                        href="/learn/aca-dt-mini-34-bk-wombot/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/csedweek/aca-dt-mini-bk-microbit-intro/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Micro:bit Starter - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about the BBC micro:bit while creating your
                        own virtual pet!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/aca-dt-mini-bk-microbit-intro/">View details</a><a
                        href="/learn/aca-dt-mini-bk-microbit-intro/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/ePxgBcqdeoESenpmSBr4a5/Cryptographyx2.svg"><a
                        class="mt-3" href="/course/cyber-78-py-crypto-noprog/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Cryptography</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn the techniques to start you on your way to
                        becoming a cyber security expert!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>3-6</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-78-py-crypto-noprog/">View details</a><a
                        href="/learn/cyber-78-py-crypto-noprog/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-py-functions-data-rep/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Data Representation - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Play with binary numbers, encrypt text, stylise
                        images and make music using Python.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-py-functions-data-rep/">View details</a><a
                        href="/learn/aca-dt-py-functions-data-rep/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/NXmJDW5CkAHbbJ7LoyE2LW/WebAppSecurity.svg"><a
                        class="mt-3" href="/course/cyber-hs-websec-v2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Web Application Security</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn the tools and techniques to start you on
                        your way to becoming a cyber security expert!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-hs-websec-v2/">View details</a><a href="/learn/cyber-hs-websec-v2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-virtual-pet.svg"><a
                        class="mt-3" href="/csedweek/hoc-virtual-pet/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Virtual Pet micro:bit - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming with the BBC
                        micro:bit.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-virtual-pet/">View details</a><a href="/learn/hoc-virtual-pet/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/BRsPkmWLTHcSQqKm7ELzd3/NetworkSecurityx2.svg"><a
                        class="mt-3" href="/course/cyber-910-py-networking-v2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Network Security</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn the techniques and code to start you on your
                        way to becoming a cyber security expert!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-910-py-networking-v2/">View details</a><a
                        href="/learn/cyber-910-py-networking-v2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-frozen-fractals-blockly.svg"><a
                        class="mt-3" href="/csedweek/hoc-snowflake-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Frozen Fractals - Blockly
                            Turtle</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-snowflake-blockly/">View details</a><a href="/learn/hoc-snowflake-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Recent
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/5A4QjQcPZpYEwwq6vWr38E/js-yellow.svg"><a class="mt-3"
                        href="/course/intro-js-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Webpages - JavaScript</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to make interactive web pages with
                        JavaScript, and build your own puzzle game!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">JavaScript</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/intro-js-1/">View details</a><a href="/learn/intro-js-1/module-3/22/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/blockly-python-blue.svg"><a
                        class="mt-3" href="/course/blockly-for-beginners/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Blockly for Beginners</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Perfect for beginners of all ages learning to code
                        visually with blocks.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>10</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/blockly-for-beginners/">View details</a><a href="/learn/blockly-for-beginners/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-frozen-fractals.svg"><a
                        class="mt-3" href="/csedweek/hoc-snowflake/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Frozen Fractals - Python Turtle
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-snowflake/">View details</a><a href="/learn/hoc-snowflake/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-orange-brown.svg"><a
                        class="mt-3" href="/csedweek/hoc-mud/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">The Dark Tunnel - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-mud/">View details</a><a href="/learn/hoc-mud/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Recent
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-green.svg"><a
                        class="mt-3" href="/gym/web-playground/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground- HTML/CSS/JS</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Workspace for your own web programs.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">HTML/CSS</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">JavaScript</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>5</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/web-playground/">View details</a><a href="/learn/web-playground/2/3/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Recent
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-56-bk-cookie/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Cookie Clicker - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Code a simple web game and click as many cookies
                        as you can!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">JavaScript</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-56-bk-cookie/">View details</a><a
                        href="/learn/aca-dt-56-bk-cookie/playgrounds/2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-56-bk-microbit-sport/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Sport micro:bit - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Combine Health and Physical Education and Digital
                        Technologies!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-56-bk-microbit-sport/">View details</a><a
                        href="/learn/aca-dt-56-bk-microbit-sport/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-pink.svg"><a
                        class="mt-3" href="/csedweek/hoc-eliza/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Is Eliza Human? - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-eliza/">View details</a><a href="/learn/hoc-eliza/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/fncP6BCQ9YixsCZ8u5GPjA/GDB-469UIUXIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-6/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Visual
                            Design (UI/UX)</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of digital technologies.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-6/">View details</a><a href="/learn/digital-exploration-6/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/oGbm9jpXkeKF6fii9kUTW8/threat-modelling-icon.svg"><a
                        class="mt-3" href="/course/cyber-910-mct/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Modelling Cyber Threats</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">How do experts know the security risks they face
                        in digital systems?</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-910-mct/">View details</a><a href="/learn/cyber-910-mct/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-neon-green-black.svg"><a
                        class="mt-3" href="/csedweek/hoc-space/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Space - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming and reach for the
                        stars!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-space/">View details</a><a href="/learn/hoc-space/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-56-bk-microbit-garden/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Smart Garden micro:bit -
                            Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about the BBC micro:bit while creating your
                        own super-sensing Smart Garden!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-56-bk-microbit-garden/">View details</a><a
                        href="/learn/aca-dt-56-bk-microbit-garden/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-purple.svg"><a
                        class="mt-3" href="/gym/gym-1a/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Coding - Python Gym</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Do a coding workout!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>7</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/gym-1a/">View details</a><a href="/learn/gym-1a/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        Practice</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-green.svg"><a
                        class="mt-3" href="/gym/python-turtle-playground/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground - Turtle Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Workspace for your own Python Turtle programs.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>5</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/python-turtle-playground/">View details</a><a href="/learn/python-turtle-playground/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        Practice</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-mini-34-bk-variables/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Blockly Starters</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn to code and work up an appetite at the same
                        time, as you take over a cooking show and help give the contestants feedback!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-6</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-mini-34-bk-variables/">View details</a><a
                        href="/learn/aca-dt-mini-34-bk-variables/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-78-py-microbit-sport/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Sport micro:bit - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Combine Health and Physical Education and Digital
                        Technologies!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6-10</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-78-py-microbit-sport/">View details</a><a
                        href="/learn/aca-dt-78-py-microbit-sport/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-biology.svg"><a
                        class="mt-3" href="/csedweek/hoc-classifier/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Animal Classifier - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Develop Python programming skills and build an
                        animal classifier!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-classifier/">View details</a><a href="/learn/hoc-classifier/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/csedweek/aca-dt-mini-78-py-microbit-radio/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Radio with micro:bit - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Program a micro:bit to create wireless networks
                        and send messages around the room!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/aca-dt-mini-78-py-microbit-radio/">View details</a><a
                        href="/learn/aca-dt-mini-78-py-microbit-radio/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-red.svg"><a class="mt-3"
                        href="/csedweek/hoc-epidemic/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Disease Epidemic - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-epidemic/">View details</a><a href="/learn/hoc-epidemic/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/csedweek/aca-dt-mini-56-bk-microbit-radio/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Radio with micro:bit - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Program a micro:bit to create wireless networks
                        and send messages around the room!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/aca-dt-mini-56-bk-microbit-radio/">View details</a><a
                        href="/learn/aca-dt-mini-56-bk-microbit-radio/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-hydrangea-danger-blockly.svg"><a
                        class="mt-3" href="/csedweek/hoc-hydrangea-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Hydrangea Danger - Blockly
                            Turtle</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Continue to build on Blockly programming skills!
                    </p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-hydrangea-blockly/">View details</a><a href="/learn/hoc-hydrangea-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/duLmLALqeAXHGaXwcQFKu/GDB-435WarehouseRobotIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-3-python-turtle/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Robots in
                            the Warehouse</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of digital technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-3-python-turtle/">View details</a><a
                        href="/learn/digital-exploration-3-python-turtle/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-78-py-microbit-garden/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Smart Garden micro:bit - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about the BBC micro:bit while creating your
                        own super-sensing Smart Garden!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-78-py-microbit-garden/">View details</a><a
                        href="/learn/aca-dt-78-py-microbit-garden/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/hoc-light-blue-yellow.svg"><a
                        class="mt-3" href="/csedweek/hoc-emoticons/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Emoticon Madness - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Get a taste for programming!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/hoc-emoticons/">View details</a><a href="/learn/hoc-emoticons/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/microbit-red.svg"><a
                        class="mt-3" href="/gym/microbit-playground/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground micro:bit - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Write Python code for the micro:bit!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/microbit-playground/">View details</a><a href="/learn/microbit-playground/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        Practice</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/csedweek/aca-dt-mini-56-bk-satellite/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Satellite Turtle - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Use Blockly to draw your own awesome satellite!
                    </p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/aca-dt-mini-56-bk-satellite/">View details</a><a
                        href="/learn/aca-dt-mini-56-bk-satellite/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/microbit-red.svg"><a
                        class="mt-3" href="/gym/microbit-playground-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground micro:bit - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Write code for the micro:bit using Blockly!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>3</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/microbit-playground-blockly/">View details</a><a
                        href="/learn/microbit-playground-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        Practice</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/maths-python-green.svg"><a
                        class="mt-3" href="/course/maths-yr7/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Geometry - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Explore a different side of maths, and learn
                        Python programming along the way. For the Australian Curriculum: Mathematics Year 7.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/maths-yr7/">View details</a><a href="/learn/maths-yr7/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/python-green.svg"><a
                        class="mt-3" href="/course/nz-ncea-level1-python/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">NZ NCEA Level 1 Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Perfect for ākonga in Aotearoa New Zealand
                        studying NCEA Level 1 Digital Technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/nz-ncea-level1-python/">View details</a><a href="/learn/nz-ncea-level1-python/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-5-bk-biology/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Biology - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Combine Biology and Digital Technologies to
                        identify animals!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-5-bk-biology/">View details</a><a href="/learn/aca-dt-5-bk-biology/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/csedweek/aca-dt-mini-78-py-satellite/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Satellite Turtle - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Use Python to draw your own awesome satellite!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/aca-dt-mini-78-py-satellite/">View details</a><a
                        href="/learn/aca-dt-mini-78-py-satellite/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/BDJrAm3MosxT5EaKfGRHpR/GDB-469HomeAutoIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-4-python/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Home
                            Automation - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of digital technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-4-python/">View details</a><a
                        href="/learn/digital-exploration-4-python/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-56-bk-christmas/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Christmas micro:bit - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Program your own Christmas Tree ornaments using
                        Blockly and the BBC Micro:bit!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1-2</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-56-bk-christmas/">View details</a><a href="/learn/aca-dt-56-bk-christmas/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/r4w5jjo7rssERh4k9E5iwY/GDB-433ChatbotIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-2-python/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Chatbot -
                            Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of digital technologies</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-2-python/">View details</a><a
                        href="/learn/digital-exploration-2-python/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Recent
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-green.svg"><a
                        class="mt-3" href="/gym/blockly-turtle-playground/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground - Turtle Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Workspace for your own Turtle Blockly programs.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>5</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/blockly-turtle-playground/">View details</a><a
                        href="/learn/blockly-turtle-playground/B/4/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-56-bk-assessment/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Blockly - Assessment</h5>
                    </a>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                module</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-56-bk-assessment/">View details</a><a
                        href="/learn/aca-dt-56-bk-assessment/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/python-yellow.svg"><a
                        class="mt-3" href="/course/image-manipulation-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Image Manipulation - Python
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Extend your Python skills to edit and manipulate
                        your images.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/image-manipulation-1/">View details</a><a href="/learn/image-manipulation-1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/JAVmkxHmNacMkHupALQ6xd/purplegrok1.png"><a
                        class="mt-3" href="/csedweek/image-magic/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Image Magic - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Dip your toes into the world of image
                        manipulation. Use code to edit images, just like magic!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/image-magic/">View details</a><a href="/learn/image-magic/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/csedweek/aca-dt-mini-bk-microbit-rocket/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Blast-off micro:bit - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Prepare for launch with Blockly and the micro:bit
                        to make a rocket ship, complete with countdown!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/aca-dt-mini-bk-microbit-rocket/">View details</a><a
                        href="/learn/aca-dt-mini-bk-microbit-rocket/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-7-bk-geometry/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Geometry - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Explore geometry through programming, and draw
                        intricate patterns and explosive fireworks!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-7-bk-geometry/">View details</a><a href="/learn/aca-dt-7-bk-geometry/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/r4w5jjo7rssERh4k9E5iwY/GDB-433ChatbotIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-2-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Chatbot -
                            Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of digital technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-2-blockly/">View details</a><a
                        href="/learn/digital-exploration-2-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/BDJrAm3MosxT5EaKfGRHpR/GDB-469HomeAutoIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-4-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Home
                            Automation - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of digital technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-4-blockly/">View details</a><a
                        href="/learn/digital-exploration-4-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/GBrHYsw6aqM9BmLKTMZcC/VET_IN.svg"><a class="mt-3"
                        href="/course/cyber-vet/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Cyber VET Challenge - Schools
                            Cyber Security Challenges</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">You've just joined Squizzy Analytics as an intern.
                        How will you safeguard your online identity, and can you help the company successfully respond
                        to cyber incidents?</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-vet/">View details</a><a href="/learn/cyber-vet/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/yJuXuzSbLqKseN6iHG3rsB/MSNcourseicon320x320.svg"><a
                        class="mt-3" href="/course/cyber-msn-2024/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Monitoring &amp; Securing
                            Networks</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">How do experts monitor their networks, and keep
                        them secure from external threats?</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-msn-2024/">View details</a><a href="/learn/cyber-msn-2024/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/baQ8fTDc5cfvfMzdXEUoUQ/GDB-436FraudulentReviewsIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-1-blockly/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Fraudulent
                            Reviews - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of Digital Technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-1-blockly/">View details</a><a
                        href="/learn/digital-exploration-1-blockly/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/nBSTuW38jWbbJpVR7aQR7B/coursebadgecloudcomputing.svg"><a
                        class="mt-3" href="/course/dt-applied-cloud-computing/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Cloud Computing</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Demystify the cloud through a practical course,
                        developing an understanding of API functionality, the cloud, and its impact on our day-to-day
                        lives.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>8-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/dt-applied-cloud-computing/">View details</a><a
                        href="/learn/dt-applied-cloud-computing/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-7-py-biology/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Biology - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Combine Biology and Digital Technologies to build
                        an animal classifier!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-7-py-biology/">View details</a><a href="/learn/aca-dt-7-py-biology/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Recent
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-green.svg"><a
                        class="mt-3" href="/gym/blockly-playground/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground - Blockly</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Workspace for your own Blockly programs.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>5</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/blockly-playground/">View details</a><a href="/learn/blockly-playground/4/0/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Short Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/baQ8fTDc5cfvfMzdXEUoUQ/GDB-436FraudulentReviewsIcon.svg"><a
                        class="mt-3" href="/csedweek/digital-exploration-1-python/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Digital Exploration Fraudulent
                            Reviews - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Inspire your students to discover and explore the
                        exciting world of Digital Technologies.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                hour</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/csedweek/digital-exploration-1-python/">View details</a><a
                        href="/learn/digital-exploration-1-python/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/vF45DBbqxy9DPbuzQcSDW8/Unixcourseicon.png"><a
                        class="mt-3" href="/course/cyber-unix/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Unix</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Become a computer ninja by learning skills in
                        using Unix and the command line!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Bash</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>10-15</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cyber-unix/">View details</a><a href="/learn/cyber-unix/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/4dSNiE2kKVhdoxk9PwX67R/Quantumcourseicon1.svg"><a
                        class="mt-3" href="/course/quantum-computing/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Quantum Computing 1</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Enter the tiny, cold and weird quantum world.
                        Learn about the next generation of computers and how they compare to today's computers.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2-4</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/quantum-computing/">View details</a><a href="/learn/quantum-computing/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/TAAKTrVgBrbLUdARG9Wuhb/databases-green2x.png"><a
                        class="mt-3" href="/gym/playground-sql/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Playground - SQL</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Workspace for your own SQL queries.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">SQL</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/playground-sql/">View details</a><a href="/learn/playground-sql/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        Practice</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-mini-78-js-geography/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Data Interpretation Geography -
                            HTML, CSS, JS</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Use JavaScript and quizzes to interpret and
                        annotate geographical maps.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">JavaScript</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>3</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-mini-78-js-geography/">View details</a><a
                        href="/learn/aca-dt-mini-78-js-geography/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/kyzP3PPknWYnZei4fdGSHa/GDB-337DataSci1Logo.svg"><a
                        class="mt-3" href="/course/cme-data-science1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Data Science - An Introduction
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">An introduction to the field of data science.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-data-science1/">View details</a><a href="/learn/cme-data-science1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/LDtMmUWbcMLWmraWvw2hmk/GDB-337DataSci2Logo.svg"><a
                        class="mt-3" href="/course/cme-data-science2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Data Science - Mystery of the
                            Lost Mine</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Travel through the Pilbara to solve the Mystery of
                        the Lost Mine, using data science.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-data-science2/">View details</a><a href="/learn/cme-data-science2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/blockly-grok-blue.svg"><a
                        class="mt-3" href="/course/grok-showcase/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Grok Showcase</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">A demo course to showcase a number of features of
                        the Grok platform.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/grok-showcase/">View details</a><a href="/learn/grok-showcase/cross-language/10/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-78-py-assessment/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">DT Challenge Python -
                            Assessment</h5>
                    </a>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                module</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-78-py-assessment/">View details</a><a
                        href="/learn/aca-dt-78-py-assessment/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/NTZsxfRobdLwkQArfD5MyQ/exploration.svg"><a
                        class="mt-3" href="/course/cme-scratch-exploration/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Exploration</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about minerals and exploration by
                        programming Scratch!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Scratch</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>3</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-scratch-exploration/">View details</a><a
                        href="/learn/cme-scratch-exploration/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/6cTkjcxcrW8EeYEsTRuT7j/Sensors_r2.png"><a class="mt-3"
                        href="/course/cme-bk-auto-sensing/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Sensing - Blockly
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about remote sensing and data using
                        Resources with the Micro:bit and Blockly!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-bk-auto-sensing/">View details</a><a href="/learn/cme-bk-auto-sensing/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/3GihWx28nGySNiqmVr5Q8i/Wombotcoursebadge.svg"><a
                        class="mt-3" href="/course/cme-logo-wombot/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Wombot</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Take wombot on an adventure!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Turtle</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>1</b>
                                module</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-logo-wombot/">View details</a><a href="/learn/cme-logo-wombot/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/e58UFfBNPFB6U8Q39Yeou8/DS3courselogo.svg"><a
                        class="mt-3" href="/course/cme-data-science3/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Data Science - Data for a
                            better future</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">An introduction to using SQL in data science.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-data-science3/">View details</a><a href="/learn/cme-data-science3/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/aca-default.svg"><a
                        class="mt-3" href="/course/aca-dt-7-py-biology-extension/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Biology Extension - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Boost your programming skills with these extension
                        modules for our 7 Python + Biology challenge.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Blockly</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>6-8</b>
                                hours</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/aca-dt-7-py-biology-extension/">View details</a><a
                        href="/learn/aca-dt-7-py-biology-extension/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-blue-base">
                <div class="flex p-2 text-sm font-semibold items-center justify-center bg-blue-base text-white">Recent
                </div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Practice</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://assets.learn.groklearning-cdn.com/static/images/badges/codegym-purple.svg"><a
                        class="mt-3" href="/gym/blockly-practice-1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Blockly Practice</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Do a visual programming workout using blockly.</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>7</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/gym/blockly-practice-1/">View details</a><a href="/learn/blockly-practice-1/basics/4/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/DYopnnScbDgvoBgtvDhnF/RCA_logo_W160px-01.png"><a
                        class="mt-3" href="/course/automation-mc-auto/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Challenge: Automation
                        </h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about automation by coding your own vehicle
                        to drive itself!</p>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>5</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/automation-mc-auto/">View details</a><a href="/learn/automation-mc-auto/auv/8/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Continue</a>
                </div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/VYHB8PyPTXdsYmfjoBecyd/Sensors_r2.png"><a class="mt-3"
                        href="/course/cme-py3-auto-sensing/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Sensing - Python</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about remote sensing and data using
                        Resources with the Micro:bit and Python!</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span>
                    </div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>4</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-py3-auto-sensing/">View details</a><a href="/learn/cme-py3-auto-sensing/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/DjhiM93b7AhVvRXZbT8AoW/Auto5course_r1.svg"><a
                        class="mt-3" href="/course/cme-py3-automation-part1/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Automation - Python
                            Part 1</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about automation in Resources with the
                        micro:car and Python! This course is part 1 of 2.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-py3-automation-part1/">View details</a><a
                        href="/learn/cme-py3-automation-part1/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
            <div data-testid="course-box"
                class="flex flex-col bg-white border rounded hover:drop-shadow-md active:drop-shadow-lg border-grey-mid">
                <div class="p-2 text-sm font-semibold items-center justify-center hidden"></div>
                <div class="flex flex-1 flex-col items-top p-4 border-b border-b-grey-light">
                    <div class="flex items-center text-xs font-bold px-1 pb-1 mb-1.5"><span data-testid="content-type"
                            class="uppercase">Course</span>
                        <div class="ml-auto"></div>
                    </div><img width="90px" height="90px"
                        src="https://groklearning-cdn.com/courses/DjhiM93b7AhVvRXZbT8AoW/Auto5course_r1.svg"><a
                        class="mt-3" href="/course/cme-py3-automation-part2/">
                        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">Resources Automation - Python
                            Part 2</h5>
                    </a>
                    <p class="mb-2 font-normal text-gray-700 text-sm">Learn about automation in Resources with the
                        micro:car and Python! This course is part 2 of 2.</p>
                    <div class="flex flex-wrap gap-2 mb-2"><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">Python</span><span
                            class="grow-0 bg-blue-light-4 text-blue-base text-sm font-medium px-1 py-1.5 rounded">BBC
                            microbit</span></div>
                    <div class="flex flex-wrap items-center justify-start">
                        <div class="flex items-center whitespace-pre-wrap mr-4"><span
                                class="p-1 text-base icon icon-clock text-sm mr-1 bold"></span><span> <b>2</b>
                                modules</span></div>
                    </div>
                </div>
                <div class="px-4 py-2"><a
                        class="btn bg-transparent shadow-transparent text-base min-h-fit h-[42px] px-0 text-blue-base border-transparent hover:bg-transparent hover:border-transparent hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30"
                        href="/course/cme-py3-automation-part2/">View details</a><a
                        href="/learn/cme-py3-automation-part2/"
                        class="float-right btn text-base min-h-fit h-[42px] px-2.5 btn-outline text-blue-base border-blue-base hover:bg-blue-base/10 hover:border-blue-base hover:text-blue-base focus:bg-blue-base/10 active:bg-blue-base/30">Start
                        course</a></div>
            </div>
        </div>
    </div>
</template>

<style scoped></style>
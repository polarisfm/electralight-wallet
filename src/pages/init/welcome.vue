<template>
<q-page>

    <q-stepper class="no-shadow" ref="stepper" :color="theme == 'dark' ? 'light' : 'dark'" dark>

        <q-step default title="Welcome">

        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="640" viewBox="0 0 859.4011 184.7379"
    enable-background="new 0 0 813 107.7" xml:space="preserve">
    <g id="XMLID_1_">
    <g id="XMLID_86_">
    <linearGradient id="XMLID_17_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_111_" fill="url(#XMLID_17_)" d="M63.2,70.1c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9H12c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7c0-0.8,0.3-1.5,0.9-2.1
    c0.6-0.6,1.3-0.9,2.1-0.9h50.3c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4c0,0.8-0.3,1.5-0.9,2.1
    c-0.6,0.6-1.3,0.9-2.1,0.9H29v11.7h30.9c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4c0,0.8-0.3,1.5-0.9,2.1
    c-0.6,0.6-1.3,0.9-2.1,0.9H29v12.1H63.2z"/>
    <linearGradient id="XMLID_18_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_109_" fill="url(#XMLID_18_)" d="M131.4,70.1c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-50c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9h14.1c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v55.4H131.4z"/>
    <linearGradient id="XMLID_19_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_107_" fill="url(#XMLID_19_)" d="M197.7,70.1c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-51.2c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9h50.3c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4c0,0.8-0.3,1.5-0.9,2.1
    c-0.6,0.6-1.3,0.9-2.1,0.9h-33.3v11.7h30.9c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4c0,0.8-0.3,1.5-0.9,2.1
    c-0.6,0.6-1.3,0.9-2.1,0.9h-30.9v12.1H197.7z"/>
    <linearGradient id="XMLID_20_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_105_" fill="url(#XMLID_20_)" d="M230.5,40.5c-0.1,0.9-0.1,2.2-0.2,3.9c0,1.7-0.1,3.4-0.1,5.1c0,1.8,0,3.5,0.1,5.2
    c0,1.7,0.1,3,0.2,3.9c0.1,1.7,0.5,3.2,1,4.8c0.5,1.5,1.3,2.8,2.4,4c1.1,1.2,2.4,2.1,4.1,2.8c1.7,0.7,3.7,1,6.2,1
    c2.4,0,4.5-0.3,6-0.9c1.6-0.6,2.9-1.3,3.9-2.1c1-0.8,1.8-1.7,2.3-2.8c0.5-1,1-1.9,1.2-2.8c0.4-1.2,0.8-2,1.2-2.4
    c0.4-0.5,1.3-0.7,2.5-0.7h14.1c0.6,0,1.2,0.2,1.7,0.7c0.5,0.5,0.7,1,0.7,1.7c-0.1,3.7-1,7.1-2.7,10.4c-1.7,3.2-4.1,6-7.1,8.4
    c-3,2.4-6.6,4.3-10.6,5.7c-4.1,1.4-8.5,2.1-13.2,2.1c-5.2,0-9.8-0.8-13.9-2.3c-4.1-1.5-7.5-3.7-10.4-6.3c-2.9-2.7-5.1-5.8-6.6-9.3
    c-1.5-3.6-2.4-7.3-2.6-11.3c-0.1-3-0.2-6.1-0.2-9.5c0-3.4,0.1-6.6,0.2-9.7c0.1-4,1-7.7,2.6-11.3c1.6-3.6,3.8-6.7,6.6-9.3
    c2.8-2.7,6.3-4.8,10.4-6.3c4.1-1.5,8.7-2.3,13.9-2.3c4.8,0,9.2,0.7,13.2,2.1c4.1,1.4,7.6,3.3,10.6,5.7c3,2.4,5.4,5.2,7.1,8.4
    c1.7,3.2,2.6,6.7,2.7,10.4c0,0.6-0.2,1.2-0.7,1.7c-0.5,0.5-1,0.7-1.7,0.7h-14.1c-1.2,0-2.1-0.2-2.5-0.7c-0.4-0.5-0.8-1.3-1.2-2.4
    c-0.3-0.9-0.7-1.8-1.2-2.8c-0.5-1-1.3-1.9-2.3-2.8c-1-0.8-2.3-1.5-3.9-2.1c-1.6-0.6-3.6-0.9-6-0.9c-2.4,0-4.5,0.3-6.2,1
    c-1.7,0.7-3,1.6-4.1,2.8c-1.1,1.2-1.9,2.5-2.4,4C230.9,37.2,230.6,38.8,230.5,40.5z"/>
    <linearGradient id="XMLID_21_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_103_" fill="url(#XMLID_21_)" d="M344.4,11.8c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v11.4
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-19v55.4c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-14.1
    c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V29h-19c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9H344.4z"/>
    <linearGradient id="XMLID_22_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_100_" fill="url(#XMLID_22_)" d="M389.2,11.8c4.8,0,9,0.5,12.7,1.5c3.7,1,6.9,2.5,9.6,4.5c2.6,2,4.6,4.6,6,7.7
    s2.1,6.8,2.1,11c0,5.4-1.1,9.9-3.3,13.4c-2.2,3.6-5.4,6.3-9.5,8.2l13.4,25.7c0.2,0.4,0.3,0.8,0.3,1.2c0,0.6-0.2,1.2-0.7,1.7
    c-0.5,0.5-1,0.7-1.7,0.7h-14.7c-1.4,0-2.5-0.3-3.1-1c-0.6-0.6-1.1-1.3-1.5-1.9l-12-23.1H377v23.1c0,0.8-0.3,1.5-0.9,2.1
    c-0.6,0.6-1.3,0.9-2.1,0.9h-14.1c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7c0-0.8,0.3-1.5,0.9-2.1
    c0.6-0.6,1.3-0.9,2.1-0.9H389.2z M377,44.5h12.2c3,0,5.5-0.6,7.5-1.7c2-1.2,3-3.2,3-6.3s-1-5.1-3-6.3c-2-1.2-4.5-1.7-7.5-1.7H377
    V44.5z"/>
    <linearGradient id="XMLID_23_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_97_" fill="url(#XMLID_23_)" d="M472.1,11.8c1.4,0,2.5,0.4,3.3,1.2c0.8,0.8,1.3,1.6,1.6,2.4l23.5,68
    c0.3,0.7,0.4,1.3,0.4,1.6c0,0.6-0.2,1.2-0.7,1.7c-0.5,0.5-1,0.7-1.7,0.7h-13.6c-1.4,0-2.5-0.3-3.1-0.9c-0.6-0.6-1-1.2-1.1-1.8
    l-3-9h-28.7l-3,9c-0.1,0.6-0.5,1.2-1.1,1.8c-0.6,0.6-1.6,0.9-3.1,0.9h-13.6c-0.6,0-1.2-0.2-1.7-0.7c-0.5-0.5-0.7-1-0.7-1.7
    c0-0.4,0.1-0.9,0.4-1.6l23.5-68c0.3-0.8,0.8-1.6,1.6-2.4c0.8-0.8,1.9-1.2,3.3-1.2H472.1z M454.6,59h17.5L463.3,33L454.6,59z"/>
    <linearGradient id="XMLID_24_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_95_" fill="url(#XMLID_24_)" d="M558.2,77.6c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v3.9
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-44c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9h4.4c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v63H558.2z"/>
    <linearGradient id="XMLID_25_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_93_" fill="url(#XMLID_25_)" d="M575.4,87.4c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9h4.4c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v69.8c0,0.8-0.3,1.5-0.9,2.1
    c-0.6,0.6-1.3,0.9-2.1,0.9H575.4z"/>
    <linearGradient id="XMLID_26_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_91_" fill="url(#XMLID_26_)" d="M598.5,39.7c0.1-4,0.8-7.7,2.1-11.2c1.3-3.5,3.2-6.6,5.7-9.3
    c2.6-2.7,5.7-4.8,9.6-6.3c3.8-1.5,8.3-2.3,13.5-2.3c4.9,0,9.2,0.7,12.9,2.2c3.7,1.4,6.8,3.2,9.3,5.3c2.5,2.1,4.4,4.4,5.6,6.8
    c1.3,2.4,1.9,4.6,2,6.5c0.1,0.6-0.1,1.2-0.6,1.7c-0.5,0.5-1.1,0.7-1.7,0.7h-4.4c-1.7,0-2.8-0.4-3.1-1.2c-0.9-1.7-1.9-3.3-3-4.9
    c-1.1-1.5-2.4-2.8-3.9-3.9s-3.3-1.9-5.5-2.6c-2.1-0.6-4.6-1-7.5-1c-3,0-5.7,0.4-8.2,1.2c-2.5,0.8-4.6,2.1-6.4,3.7
    c-1.8,1.7-3.2,3.7-4.3,6.2c-1.1,2.5-1.7,5.4-1.7,8.7c-0.1,3.2-0.2,6.2-0.2,9c0,2.7,0.1,5.7,0.2,9c0.1,3.5,0.6,6.5,1.7,9.1
    c1.1,2.6,2.5,4.7,4.3,6.4c1.8,1.7,3.9,3,6.4,3.8c2.5,0.8,5.2,1.2,8.2,1.2c2.9,0,5.6-0.4,8.1-1.1c2.5-0.7,4.7-1.9,6.6-3.5
    c1.9-1.6,3.3-3.7,4.4-6.3c1-2.6,1.6-5.8,1.6-9.5v-3h-15.6c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1v-3.9
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9h22.9c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v10.3c0,4.3-0.7,8.3-2.1,11.9
    c-1.4,3.6-3.4,6.8-6,9.4c-2.6,2.6-5.9,4.7-9.7,6.2c-3.9,1.5-8.2,2.2-13.1,2.2c-5.2,0-9.7-0.8-13.5-2.3c-3.8-1.5-7-3.7-9.5-6.3
    c-2.5-2.7-4.4-5.8-5.7-9.4c-1.3-3.6-2-7.5-2.2-11.7C598.3,52.4,598.3,46.1,598.5,39.7z"/>
    <linearGradient id="XMLID_27_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_89_" fill="url(#XMLID_27_)" d="M730.8,11.8c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v69.8
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-4.4c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1V54h-38v30.5
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-4.4c-0.8,0-1.5-0.3-2.1-0.8c-0.6-0.5-0.9-1.2-0.9-2.1V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9h4.4c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v29.6h38V14.7
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9H730.8z"/>
    <linearGradient id="XMLID_28_" gradientUnits="userSpaceOnUse" x1="405.5237" y1="88.4414" x2="405.5237" y2="10.6811">
    <stop  offset="0" style="stop-color:#2484C6"/>
    <stop  offset="1" style="stop-color:#75CEDC;stop-opacity:0.2"/>
    </linearGradient>
    <path id="XMLID_87_" fill="url(#XMLID_28_)" d="M799.1,11.8c0.8,0,1.5,0.3,2.1,0.9c0.6,0.6,0.9,1.3,0.9,2.1v3.9
    c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-20.2v63c0,0.8-0.3,1.5-0.9,2.1c-0.6,0.6-1.3,0.9-2.1,0.9h-4.4
    c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1v-63h-20.2c-0.8,0-1.5-0.3-2.1-0.9c-0.6-0.6-0.9-1.3-0.9-2.1v-3.9
    c0-0.8,0.3-1.5,0.9-2.1c0.6-0.6,1.3-0.9,2.1-0.9H799.1z"/>
    </g>
    </g>
    </svg>

            <div>Version: ElectraLight v{{version}}-v{{daemonVersion}}</div>

            <h6 class="q-mb-md" style="font-weight: 300">Select Appearance:</h6>

            <q-btn-toggle
                v-model="choose_theme"
                toggle-color="primary"
                size="md"
                :options="[
                          {label: 'Light theme', value: 'light', icon: 'brightness_5'},
                          {label: 'Dark theme', value: 'dark', icon: 'brightness_2'},
                          ]"
                />


            <h6 class="q-mb-md" style="font-weight: 300">Select language:</h6>

            <q-btn-toggle
                v-model="choose_lang"
                toggle-color="primary"
                size="md"
                :options="[
                          {label: 'English', value: 'EN', icon: 'language'},
                          ]"
                />

            <p class="q-mt-md">More languages coming soon</p>

        </q-step>

        <q-step title="Configure">

            <SettingsGeneral ref="settingsGeneral"></SettingsGeneral>

        </q-step>

        <q-step title="Review">

            <h2 class="q-mt-none q-mb-none text-weight-thin">You're almost set!</h2>

            <h6 class="q-mb-md q-mt-md" style="font-weight: 300">Review settings:</h6>

            <p>You are using a
                <template v-if="pending_config.daemon.type == 'local'">
                    <code>local node</code>
                </template>
                <template v-if="pending_config.daemon.type == 'local_remote'">
                    <code>local + remote node</code>
                </template>
                <template v-if="pending_config.daemon.type == 'remote'">
                    <code>remote node</code>
                </template>
                <template v-if="pending_config.app.testnet">
                    <code>on testnet</code>
                </template>
                and will store data in
                <code>{{ pending_config.app.data_dir }}</code>
            </p>

            <p>Press next to get started!</p>

        </q-step>

    </q-stepper>

    <q-layout-footer class="no-shadow q-pa-sm">
        <div class="row justify-end">
            <div>
	        <q-btn
	            flat
	            @click="clickPrev()"
	            label="Back"
	            />
            </div>
            <div>
	        <q-btn
                    class="q-ml-sm"
                    color="primary"
	            @click="clickNext()"
	            label="Next"
	            />
            </div>
        </div>

    </q-layout-footer>

</q-page>
</template>

<script>
import { version, daemonVersion } from "../../../package.json"
import { mapState } from "vuex"
import SettingsGeneral from "components/settings_general"
export default {
    computed: mapState({
        theme: state => state.gateway.app.config.appearance.theme,
        pending_config: state => state.gateway.app.pending_config
    }),
    data() {
        return {
            choose_theme: "dark",
            choose_lang: "EN",
            version: "",
            daemonVersion: ""
        }
    },
    watch: {
        choose_theme: function (val) {
            this.$store.commit("gateway/set_app_data", {
                config: {
                    appearance: {
                        theme: val
                    }
                }
            });
        }
    },
    mounted () {

        this.version = version
        this.daemonVersion = daemonVersion

        // set add status back to 2
        this.$store.commit("gateway/set_app_data", {
            status: {
                code: 2 // Loading config
            }
        });
    },
    methods: {
        clickNext () {
            if(this.$refs.stepper.steps[this.$refs.stepper.length-1].active) {
                this.$gateway.send("core", "save_config_init", this.pending_config);
                this.$router.replace({ path: "/" });
            } else {
                this.$refs.stepper.next();
            }
        },
        clickPrev () {
            this.$refs.stepper.previous();
        },
    },
    components: {
        SettingsGeneral
    }
}
</script>

<style lang="scss">

.language-item {

    padding: 10px 30px 10px 20px;
    border: 1px solid #ccc;
    cursor: pointer;


    .language-item-circle {
        background: #cc90e2;
        width: 50px;
        height: 50px;
        border-radius: 25px;
        display: inline-block;
        line-height: 50px;
        text-align:center;
        color: white;
        margin-right: 10px;
    }
}

.q-stepper-header {
    min-height: 50px;

    .q-stepper-tab {
        padding-top: 0;
        padding-bottom: 0;
    }

}
</style>

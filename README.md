<svg xmlns="http://www.w3.org/2000/svg"
     viewBox="0 0 1441 302"
     width="1441"
     height="302"
     style="background:#262c36">

    <defs>
        <!-- Glow -->
        <filter id="glow">
            <feGaussianBlur stdDeviation="4" result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Stronger glow for meteors -->
        <filter id="meteorGlow">
            <feGaussianBlur stdDeviation="3" result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Gradient for waves -->
        <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#ffffff"/>
            <stop offset="50%" stop-color="#000000"/>
            <stop offset="100%" stop-color="#ffffff"/>
        </linearGradient>

        <!-- Gradient for glowing circle -->
        <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#ffffff"/>
            <stop offset="50%" stop-color="#000000"/>
            <stop offset="100%" stop-color="#ffffff"/>
        </linearGradient>

        <!-- Meteor trail gradients -->
        
        <linearGradient id="trail-1" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#339933" stop-opacity="0"/>
            <stop offset="100%" stop-color="#339933" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-3" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
            <stop offset="100%" stop-color="#ffffff" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1775511868966" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#040506" stop-opacity="0"/>
            <stop offset="100%" stop-color="#040506" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1775511904086" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#F7DF1E" stop-opacity="0"/>
            <stop offset="100%" stop-color="#F7DF1E" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1775511911151" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#394aab" stop-opacity="0"/>
            <stop offset="100%" stop-color="#394aab" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1775511919978" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#336791" stop-opacity="0"/>
            <stop offset="100%" stop-color="#336791" stop-opacity="1"/>
        </linearGradient>

        <!-- Circle clip for avatar -->
        <clipPath id="avatarClip">
            <circle cx="720.5" cy="151" r="65"/>
        </clipPath>
    </defs>

    <!-- Background waves -->
    <path d="M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151"
          fill="none"
          stroke="url(#waveGrad)"
          stroke-width="2"
          opacity="0.5">
        <animate attributeName="d"
                 dur="6s"
                 repeatCount="indefinite"
                 values="
             M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151;
             M0 151 Q180 181 360 151 T721 151 T1081 151 T1441 151;
             M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151"/>
    </path>

    <!-- ========== METEOR LOGOS ========== -->
    
            <!-- logos:nodejs-icon Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="100" y1="-50" x2="112.94095225512604" y2="-1.7037086855465873" stroke="url(#trail-1)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="100;216.98620838633937" dur="10s" repeatCount="indefinite" begin="0s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="0s"/>
                    <animate attributeName="x2" values="112.94095225512604;229.9271606414654" dur="10s" repeatCount="indefinite" begin="0s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="0s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIwLjg5ZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjU2IDI4OSI+PHBhdGggZmlsbD0iIzUzOWU0MyIgZD0iTTEyOCAyODguNDY0Yy0zLjk3NSAwLTcuNjg1LTEuMDYtMTEuMTMtMi45MTVsLTM1LjI0Ny0yMC45MzZjLTUuMy0yLjkxNS0yLjY1LTMuOTc1LTEuMDYtNC41MDVjNy4xNTUtMi4zODUgOC40OC0yLjkxNSAxNS45LTcuMTU2Yy43OTYtLjUzIDEuODU2LS4yNjUgMi42NS4yNjVsMjcuMDMyIDE2LjE2NmMxLjA2LjUzIDIuMzg1LjUzIDMuMTggMGwxMDUuNzQtNjEuMjE3YzEuMDYtLjUzIDEuNTktMS41OSAxLjU5LTIuOTE1VjgzLjA4YzAtMS4zMjUtLjUzLTIuMzg1LTEuNTktMi45MTVsLTEwNS43NC02MC45NTNjLTEuMDYtLjUzLTIuMzg1LS41My0zLjE4IDBMMjAuNDA1IDgwLjE2NmMtMS4wNi41My0xLjU5IDEuODU1LTEuNTkgMi45MTV2MTIyLjE3YzAgMS4wNi41MyAyLjM4NSAxLjU5IDIuOTE1bDI4Ljg4NyAxNi42OTVjMTUuNjM2IDcuOTUgMjUuNDQtMS4zMjUgMjUuNDQtMTAuNlY5My42OGMwLTEuNTkgMS4zMjYtMy4xOCAzLjE4MS0zLjE4aDEzLjUxNmMxLjU5IDAgMy4xOCAxLjMyNSAzLjE4IDMuMTh2MTIwLjU4YzAgMjAuOTM2LTExLjM5NiAzMy4xMjYtMzEuMjcyIDMzLjEyNmMtNi4wOTUgMC0xMC44NjUgMC0yNC4zOC02LjYyNWwtMjcuODI3LTE1LjlDNC4yNCAyMjAuODg1IDAgMjEzLjQ2NSAwIDIwNS41MTVWODMuMzQ2QzAgNzUuMzk2IDQuMjQgNjcuOTc2IDExLjEzIDY0TDExNi44NyAyLjc4M2M2LjYyNS0zLjcxIDE1LjYzNS0zLjcxIDIyLjI2IDBMMjQ0Ljg3IDY0QzI1MS43NiA2Ny45NzUgMjU2IDc1LjM5NSAyNTYgODMuMzQ2djEyMi4xN2MwIDcuOTUtNC4yNCAxNS4zNy0xMS4xMyAxOS4zNDVMMTM5LjEzIDI4Ni4wOGMtMy40NDUgMS41OS03LjQyIDIuMzg1LTExLjEzIDIuMzg1bTMyLjU5Ni04NC4wMDljLTQ2LjM3NyAwLTU1LjkxNy0yMS4yLTU1LjkxNy0zOS4yMjFjMC0xLjU5IDEuMzI1LTMuMTggMy4xOC0zLjE4aDEzLjc4YzEuNTkgMCAyLjkxNiAxLjA2IDIuOTE2IDIuNjVjMi4xMiAxNC4wNDUgOC4yMTUgMjAuOTM2IDM2LjMwNiAyMC45MzZjMjIuMjYxIDAgMzEuODAyLTUuMDM1IDMxLjgwMi0xNi45NmMwLTYuODkxLTIuNjUtMTEuOTI2LTM3LjM2Ny0xNS4zNzJjLTI4Ljg4Ni0yLjkxNS00Ni45MDctOS4yNzUtNDYuOTA3LTMyLjMzYzAtMjEuNDY3IDE4LjAyLTM0LjE4NyA0OC4yMzItMzQuMTg3YzMzLjkyMSAwIDUwLjYxNyAxMS42NiA1Mi43MzcgMzcuMTAxcTAgMS4xOTMtLjc5NSAyLjM4NWMtLjUzLjUzLTEuMzI1IDEuMDYtMi4xMiAxLjA2aC0xMy43OGMtMS4zMjYgMC0yLjY1LTEuMDYtMi45MTYtMi4zODVjLTMuMTgtMTQuNTc1LTExLjM5NS0xOS4zNDUtMzMuMTI2LTE5LjM0NWMtMjQuMzggMC0yNy4yOTYgOC40OC0yNy4yOTYgMTQuODRjMCA3LjY4NiAzLjQ0NSAxMC4wNyAzNi4zMDYgMTQuMzFjMzIuNTk3IDQuMjQgNDcuOTY3IDEwLjMzNiA0Ny45NjcgMzMuMTI3Yy0uMjY1IDIzLjMyMS0xOS4zNDUgMzYuNTcxLTUzLjAwMiAzNi41NzEiLz48L3N2Zz4=" width="32" height="32" x="96.94095225512604" y="-17.703708685546587" >
                    <animate attributeName="x" values="96.94095225512604;213.9271606414654" dur="10s" repeatCount="indefinite" begin="0s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="0s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="0s"/>
            </g>

            <!-- mdi:github Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="500" y1="-50" x2="512.940952255126" y2="-1.7037086855465873" stroke="url(#trail-3)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="500;616.9862083863394" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="x2" values="512.940952255126;629.9271606414654" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="6s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTEyIDJBMTAgMTAgMCAwIDAgMiAxMmMwIDQuNDIgMi44NyA4LjE3IDYuODQgOS41Yy41LjA4LjY2LS4yMy42Ni0uNXYtMS42OWMtMi43Ny42LTMuMzYtMS4zNC0zLjM2LTEuMzRjLS40Ni0xLjE2LTEuMTEtMS40Ny0xLjExLTEuNDdjLS45MS0uNjIuMDctLjYuMDctLjZjMSAuMDcgMS41MyAxLjAzIDEuNTMgMS4wM2MuODcgMS41MiAyLjM0IDEuMDcgMi45MS44M2MuMDktLjY1LjM1LTEuMDkuNjMtMS4zNGMtMi4yMi0uMjUtNC41NS0xLjExLTQuNTUtNC45MmMwLTEuMTEuMzgtMiAxLjAzLTIuNzFjLS4xLS4yNS0uNDUtMS4yOS4xLTIuNjRjMCAwIC44NC0uMjcgMi43NSAxLjAyYy43OS0uMjIgMS42NS0uMzMgMi41LS4zM3MxLjcxLjExIDIuNS4zM2MxLjkxLTEuMjkgMi43NS0xLjAyIDIuNzUtMS4wMmMuNTUgMS4zNS4yIDIuMzkuMSAyLjY0Yy42NS43MSAxLjAzIDEuNiAxLjAzIDIuNzFjMCAzLjgyLTIuMzQgNC42Ni00LjU3IDQuOTFjLjM2LjMxLjY5LjkyLjY5IDEuODVWMjFjMCAuMjcuMTYuNTkuNjcuNUMxOS4xNCAyMC4xNiAyMiAxNi40MiAyMiAxMkExMCAxMCAwIDAgMCAxMiAyIi8+PC9zdmc+" width="32" height="32" x="496.94095225512604" y="-17.703708685546587" >
                    <animate attributeName="x" values="496.94095225512604;613.9271606414654" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="6s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="6s"/>
            </g>

            <!-- devicon:n8n-wordmark Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="296.5525488069786" y1="-50" x2="309.49350106210466" y2="-1.7037086855465873" stroke="url(#trail-1775511868966)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="296.5525488069786;413.538757193318" dur="10s" repeatCount="indefinite" begin="9.7s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="9.7s"/>
                    <animate attributeName="x2" values="309.49350106210466;426.47970944844405" dur="10s" repeatCount="indefinite" begin="9.7s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="9.7s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMTI4IDEyOCI+PGcgZmlsbD0ibm9uZSI+PHBhdGggZmlsbD0iI2VhNGI3MSIgZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNNjAuNjIgNjAuNDM0YTcuMTM1IDcuMTM1IDAgMCAxLTYuOTA3LTUuMzQ5SDQ1LjU0YTMuNTY2IDMuNTY2IDAgMCAwLTMuNTE3IDIuOThsLS4yOTMgMS43NTlBNy4xIDcuMSAwIDAgMSAzOS40MSA2NGE3LjEgNy4xIDAgMCAxIDIuMzE4IDQuMTc2bC4yOTMgMS43NTlhMy41NjYgMy41NjYgMCAwIDAgMy41MTcgMi45OGgxLjA0M2E3LjEzMiA3LjEzMiAwIDEgMSAwIDMuNTY2aC0xLjA0M2E3LjEzIDcuMTMgMCAwIDEtNy4wMzUtNS45NmwtLjI5My0xLjc1OGEzLjU2NiAzLjU2NiAwIDAgMC0zLjUxNy0yLjk4aC0yLjgyNWE3LjEzNSA3LjEzNSAwIDAgMS0xMy44MTUgMEgxNC4wNGE3LjEzMiA3LjEzMiAwIDEgMSAwLTMuNTY2aDQuMDE1YTcuMTM1IDcuMTM1IDAgMCAxIDEzLjgxNSAwaDIuODI1YzEuNzQzIDAgMy4yMy0xLjI2IDMuNTE3LTIuOThsLjI5My0xLjc1OGE3LjEzIDcuMTMgMCAwIDEgNy4wMzUtNS45Nmg4LjE3NGE3LjEzMiA3LjEzMiAwIDEgMSA2LjkwNyA4LjkxNW0wLTMuNTY2YTMuNTY2IDMuNTY2IDAgMSAwIDAtNy4xMzJhMy41NjYgMy41NjYgMCAwIDAgMCA3LjEzMk03LjEzMyA2Ny41NjZhMy41NjYgMy41NjYgMCAxIDAgMC03LjEzMmEzLjU2NiAzLjU2NiAwIDAgMCAwIDcuMTMyTTI4LjUyNyA2NGEzLjU2NiAzLjU2NiAwIDEgMS03LjEzMSAwYTMuNTY2IDMuNTY2IDAgMCAxIDcuMTMxIDBtMjguNTI4IDEwLjY5OGEzLjU2NiAzLjU2NiAwIDEgMS03LjEzMiAwYTMuNTY2IDMuNTY2IDAgMCAxIDcuMTMyIDAiIGNsaXAtcnVsZT0iZXZlbm9kZCIvPjxwYXRoIGZpbGw9IiMwNDA1MDYiIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTEwNi45ODMgNjEuNTl2LS4xN2MxLjI0NC0uNjI0IDIuNDg4LTEuNyAyLjQ4OC0zLjgyNGMwLTMuMDU5LTIuNTE3LTQuOS01Ljk5NS00LjljLTMuNTYzIDAtNi4xMDggMS45NTQtNi4xMDggNC45NTdjMCAyLjAzOSAxLjE4OCAzLjE0MyAyLjQ4OSAzLjc2NnYuMTdhNC44MSA0LjgxIDAgMCAwLTMuMTY3IDQuNTg5YzAgMy4wODcgMi41NDUgNS4yNCA2Ljc1OCA1LjI0czYuNjczLTIuMTUzIDYuNjczLTUuMjRjMC0yLjU1LTEuNjk2LTQuMDUtMy4xMzgtNC41ODltLTMuNTM1LTYuMjg4YzEuNDE0IDAgMi40Ni45MDYgMi40NiAyLjQzNWMwIDEuNTMtMS4wNzUgMi40MzYtMi40NiAyLjQzNnMtMi41NDUtLjkwNi0yLjU0NS0yLjQzNmMwLTEuNTU3IDEuMTAzLTIuNDM1IDIuNTQ1LTIuNDM1bTAgMTMuMzk2Yy0xLjY0IDAtMi45Ny0xLjA0OC0yLjk3LTIuODMyYzAtMS42MTQgMS4xMDMtMi44MzIgMi45NDEtMi44MzJjMS44MSAwIDIuOTEzIDEuMTkgMi45MTMgMi44ODljMCAxLjcyNy0xLjI3MiAyLjc3NS0yLjg4NCAyLjc3NSIgY2xpcC1ydWxlPSJldmVub2RkIi8+PHBhdGggZmlsbD0iIzA0MDUwNiIgZD0iTTExNC40ODQgNzEuMTM0aDMuNjE5di03LjY3NWMwLTIuNTIxIDEuNTI3LTMuNjI2IDMuMjUyLTMuNjI2YzEuNjk2IDAgMy4wMjYgMS4xMzMgMy4wMjYgMy40NTZ2Ny44NDVIMTI4di04LjU4MmMwLTMuNzEtMi4xNS01Ljg2Mi01LjUxNC01Ljg2MmMtMi4xMiAwLTMuMzA5Ljg1LTQuMTU3IDEuOTU0aC0uMjI2bC0uMzExLTEuNjcxaC0zLjMwOHptLTMyLjA0IDBoLTMuNjJWNTYuOTczaDMuMzA5bC4zMSAxLjY3aC4yMjdjLjg0OC0xLjEwNCAyLjAzNi0xLjk1MyA0LjE1Ny0xLjk1M2MzLjM2NSAwIDUuNTE0IDIuMTUyIDUuNTE0IDUuODYydjguNTgyaC0zLjYydi03Ljg0NWMwLTIuMzIzLTEuMzI5LTMuNDU2LTMuMDI1LTMuNDU2Yy0xLjcyNSAwLTMuMjUyIDEuMTA1LTMuMjUyIDMuNjI2eiIvPjwvZz48L3N2Zz4=" width="32" height="32" x="293.49350106210466" y="-17.703708685546587" >
                    <animate attributeName="x" values="293.49350106210466;410.47970944844405" dur="10s" repeatCount="indefinite" begin="9.7s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="9.7s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="9.7s"/>
            </g>

            <!-- logos:javascript Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="679.6288698125193" y1="-50" x2="692.5698220676453" y2="-1.7037086855465873" stroke="url(#trail-1775511904086)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="679.6288698125193;796.6150781988587" dur="10s" repeatCount="indefinite" begin="3.8s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="3.8s"/>
                    <animate attributeName="x2" values="692.5698220676453;809.5560304539847" dur="10s" repeatCount="indefinite" begin="3.8s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="3.8s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiI+PHBhdGggZmlsbD0iI2Y3ZGYxZSIgZD0iTTAgMGgyNTZ2MjU2SDB6Ii8+PHBhdGggZD0ibTY3LjMxMiAyMTMuOTMybDE5LjU5LTExLjg1NmMzLjc4IDYuNzAxIDcuMjE4IDEyLjM3MSAxNS40NjUgMTIuMzcxYzcuOTA1IDAgMTIuODktMy4wOTIgMTIuODktMTUuMTJ2LTgxLjc5OGgyNC4wNTd2ODIuMTM4YzAgMjQuOTE3LTE0LjYwNiAzNi4yNTktMzUuOTE2IDM2LjI1OWMtMTkuMjQ1IDAtMzAuNDE2LTkuOTY3LTM2LjA4Ny0yMS45OTZtODUuMDctMi41NzZsMTkuNTg4LTExLjM0MWM1LjE1NyA4LjQyMSAxMS44NTkgMTQuNjA3IDIzLjcxNSAxNC42MDdjOS45NjkgMCAxNi4zMjUtNC45ODQgMTYuMzI1LTExLjg1OGMwLTguMjQ4LTYuNTMtMTEuMTctMTcuNTI4LTE1Ljk4bC02LjAxMy0yLjU4Yy0xNy4zNTctNy4zODctMjguODctMTYuNjY3LTI4Ljg3LTM2LjI1N2MwLTE4LjA0NCAxMy43NDctMzEuNzkyIDM1LjIyOC0zMS43OTJjMTUuMjk0IDAgMjYuMjkyIDUuMzI4IDM0LjE5NiAxOS4yNDdsLTE4LjczMiAxMi4wM2MtNC4xMjUtNy4zODktOC41OTEtMTAuMzEtMTUuNDY1LTEwLjMxYy03LjA0NiAwLTExLjUxNCA0LjQ2OC0xMS41MTQgMTAuMzFjMCA3LjIxNyA0LjQ2OCAxMC4xNCAxNC43NzggMTQuNjA4bDYuMDE0IDIuNTc3YzIwLjQ1IDguNzY1IDMxLjk2MyAxNy43IDMxLjk2MyAzNy44MDRjMCAyMS42NTQtMTcuMDEyIDMzLjUxLTM5Ljg2NyAzMy41MWMtMjIuMzM5IDAtMzYuNzc0LTEwLjY1NC00My44MTktMjQuNTc0Ii8+PC9zdmc+" width="32" height="32" x="676.5698220676453" y="-17.703708685546587" >
                    <animate attributeName="x" values="676.5698220676453;793.5560304539847" dur="10s" repeatCount="indefinite" begin="3.8s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="3.8s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="3.8s"/>
            </g>

            <!-- skill-icons:c Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="780.4876161755253" y1="-50" x2="793.4285684306514" y2="-1.7037086855465873" stroke="url(#trail-1775511911151)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="780.4876161755253;897.4738245618647" dur="10s" repeatCount="indefinite" begin="1.6s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="1.6s"/>
                    <animate attributeName="x2" values="793.4285684306514;910.4147768169908" dur="10s" repeatCount="indefinite" begin="1.6s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="1.6s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiI+PGcgZmlsbD0ibm9uZSI+PHJlY3Qgd2lkdGg9IjI1NiIgaGVpZ2h0PSIyNTYiIGZpbGw9IiMzOTRhYWIiIHJ4PSI2MCIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xMzQuMDAxIDMzYzM1LjE0MyAwIDY1LjgyNyAxOS4wODYgODIuMjYxIDQ3LjQ1NmwtLjE2LS4yNzNsLTQxLjM0OSAyMy44MDhjLTguMTQ2LTEzLjc5My0yMy4wODEtMjMuMTAyLTQwLjIxMy0yMy4yOTNsLS41MzktLjAwM2MtMjYuMTI2IDAtNDcuMzA2IDIxLjE3OS00Ny4zMDYgNDcuMzA0YTQ3LjEgNDcuMSAwIDAgMCA2LjIzOSAyMy40N2M4LjE1NCAxNC4yMzUgMjMuNDgyIDIzLjgzNyA0MS4wNjcgMjMuODM3YzE3LjY5MiAwIDMzLjEwOC05LjcyNCA0MS4yMjEtMjQuMTExbC0uMTk3LjM0NWw0MS4yODYgMjMuOTE4Yy0xNi4yNTQgMjguMTMtNDYuNTE3IDQ3LjE1Ny04MS4yNTIgNDcuNTM2bC0xLjA1OC4wMDZjLTM1LjI1NSAwLTY2LjAyNi0xOS4yMDQtODIuNDE5LTQ3LjcyNEM0My41NzkgMTYxLjM1MyAzOSAxNDUuMjEyIDM5IDEyNy45OTlDMzkgNzUuNTMzIDgxLjUzMiAzMyAxMzQuMDAxIDMzIi8+PC9nPjwvc3ZnPg==" width="32" height="32" x="777.4285684306514" y="-17.703708685546587" >
                    <animate attributeName="x" values="777.4285684306514;894.4147768169908" dur="10s" repeatCount="indefinite" begin="1.6s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="1.6s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="1.6s"/>
            </g>

            <!-- devicon:postgresql Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="1159.3494817142878" y1="-50" x2="1172.290433969414" y2="-1.7037086855465873" stroke="url(#trail-1775511919978)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="1159.3494817142878;1276.335690100627" dur="10s" repeatCount="indefinite" begin="8.2s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="8.2s"/>
                    <animate attributeName="x2" values="1172.290433969414;1289.2766423557532" dur="10s" repeatCount="indefinite" begin="8.2s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="8.2s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMTI4IDEyOCI+PHBhdGggZD0iTTkzLjgwOSA5Mi4xMTJjLjc4NS02LjUzMy41NS03LjQ5MiA1LjQxNi02LjQzM2wxLjIzNS4xMDhjMy43NDIuMTcgOC42MzctLjYwMiAxMS41MTMtMS45MzhjNi4xOTEtMi44NzMgOS44NjEtNy42NjggMy43NTgtNi40MDljLTEzLjkyNCAyLjg3My0xNC44ODEtMS44NDItMTQuODgxLTEuODQyYzE0LjcwMy0yMS44MTUgMjAuODQ5LTQ5LjUwOCAxNS41NDMtNTYuMjg3Yy0xNC40Ny0xOC40ODktMzkuNTE3LTkuNzQ2LTM5LjkzNi05LjUybC0uMTM0LjAyNWMtMi43NTEtLjU3MS01LjgzLS45MTItOS4yODktLjk2OGMtNi4zMDEtLjEwNC0xMS4wODIgMS42NTItMTQuNzA5IDQuNDAyYzAgMC00NC42ODMtMTguNDA5LTQyLjYwNCAyMy4xNTFjLjQ0MiA4Ljg0MSAxMi42NzIgNjYuODk4IDI3LjI2IDQ5LjM2MmM1LjMzMi02LjQxMiAxMC40ODQtMTEuODM0IDEwLjQ4NC0xMS44MzRjMi41NTggMS42OTkgNS42MjIgMi41NjcgOC44MzQgMi4yNTVsLjI0OS0uMjEyYy0uMDc4Ljc5Ni0uMDQ0IDEuNTc1LjA5OSAyLjQ5N2MtMy43NTcgNC4xOTktMi42NTMgNC45MzYtMTAuMTY2IDYuNDgyYy03LjYwMiAxLjU2Ni0zLjEzNiA0LjM1NS0uMjIxIDUuMDg0YzMuNTM1Ljg4NCAxMS43MTIgMi4xMzYgMTcuMjM4LTUuNTk4bC0uMjIuODgyYzEuNDc0IDEuMTggMS4zNzUgOC40NzcgMS41ODMgMTMuNjljLjIwOSA1LjIxNC41NTggMTAuMDc5IDEuNjIxIDEyLjk0OHMyLjMxNyAxMC4yNTYgMTIuMTkxIDguMTRjOC4yNTItMS43NjQgMTQuNTYxLTQuMzA5IDE1LjEzNi0yNy45ODUiLz48cGF0aCBkPSJNNzUuNDU4IDEyNS4yNTZjLTQuMzY3IDAtNy4yMTEtMS42ODktOC45MzgtMy4zMmMtMi42MDctMi40Ni0zLjY0MS01LjYyOS00LjI1OS03LjUyMmwtLjI2Ny0uNzljLTEuMjQ0LTMuMzU4LTEuNjY2LTguMTkzLTEuOTE2LTE0LjQxOWMtLjAzOC0uOTM1LS4wNjQtMS44OTgtLjA5My0yLjkxOWMtLjAyMS0uNzQ3LS4wNDctMS42ODQtLjA4NS0yLjY2NGExOC44IDE4LjggMCAwIDEtNC45NjIgMS41NjhjLTMuMDc5LjUyNi02LjM4OS4zNTYtOS44NC0uNTA3Yy0yLjQzNS0uNjA5LTQuOTY1LTEuODcxLTYuNDA3LTMuODJjLTQuMjAzIDMuNjgxLTguMjEyIDMuMTgyLTEwLjM5NiAyLjQ1M2MtMy44NTMtMS4yODUtNy4zMDEtNC44OTYtMTAuNTQyLTExLjAzN2MtMi4zMDktNC4zNzUtNC41NDItMTAuMDc1LTYuNjM4LTE2Ljk0M2MtMy42NS0xMS45Ni01Ljk2OS0yNC41NTctNi4xNzUtMjguNjkzQzQuMjkyIDIzLjY5OCA3Ljc3NyAxNC40NCAxNS4yOTYgOS4xMjlDMjcuMTU3Ljc1MSA0NS4xMjggNS42NzggNTEuNjggNy45MTVjNC40MDItMi42NTMgOS41ODEtMy45NDQgMTUuNDMzLTMuODUxYzMuMTQzLjA1MSA2LjEzNi4zMjcgOC45MTYuODIzYzIuOS0uOTEyIDguNjI4LTIuMjIxIDE1LjE4NS0yLjEzOWMxMi4wODEuMTQ0IDIyLjA5MiA0Ljg1MiAyOC45NDkgMTMuNjE1YzQuODk0IDYuMjUyIDIuNDc0IDE5LjM4MS41OTcgMjYuNjUxYy0yLjY0MiAxMC4yMjYtNy4yNzEgMjEuMTAyLTEyLjk1NyAzMC41N2MxLjU0NC4wMTEgMy43ODEtLjE3NCA2Ljk2MS0uODMxYzYuMjc0LTEuMjk1IDguMTA5IDIuMDY5IDguNjA3IDMuNTc1YzEuOTk1IDYuMDQyLTYuNjc3IDEwLjYwOC05LjM4MiAxMS44NjRjLTMuNDY2IDEuNjA5LTkuMTE3IDIuNTg5LTEzLjc0NSAyLjM3N2wtLjIwMi0uMDEzbC0xLjIxNi0uMTA3bC0uMTIgMS4wMTRsLS4xMTYuOTkxYy0uMzExIDExLjk5OS0yLjAyNSAxOS41OTgtNS41NTIgMjQuNjE5Yy0zLjY5NyA1LjI2NC04LjgzNSA2LjczOS0xMy4zNjEgNy43MDljLTEuNTQ0LjMzLTIuOTQ3LjQ3NC00LjIxOS40NzRtLTkuMTktNDMuNjcxYzIuODE5IDIuMjU2IDMuMDY2IDYuNTAxIDMuMjg3IDE0LjQzNGMuMDI4Ljk5LjA1NCAxLjkyNy4wODkgMi44MDJjLjEwNiAyLjY1LjM1NSA4Ljg1NSAxLjMyNyAxMS40NzdjLjEzNy4zNzEuMjYuNzQ3LjM5IDEuMTQ2YzEuMDgzIDMuMzE2IDEuNjI2IDQuOTc5IDYuMzA5IDMuOTc4YzMuOTMxLS44NDMgNS45NTItMS41OTkgNy41MzQtMy44NTFjMi4yOTktMy4yNzQgMy41ODUtOS44NiAzLjgyMS0xOS41NzVsNC43ODMuMTE2bC00Ljc1LS41N2wuMTQtMS4xODZjLjQ1NS0zLjkxLjc4My02LjczNCAzLjM5Ni04LjYwMmMyLjA5Ny0xLjQ5OCA0LjQ4Ni0xLjM1MyA2LjM4OS0xLjAxYy0yLjA5MS0xLjU4LTIuNjY5LTMuNDMzLTIuODIzLTQuMTkzbC0uMzk5LTEuOTY1bDEuMTIxLTEuNjYzYzYuNDU3LTkuNTggMTEuNzgxLTIxLjM1NCAxNC42MDktMzIuMzA0YzIuOTA2LTExLjI1MSAyLjAyLTE3LjIyNiAxLjEzNC0xOC4zNTZjLTExLjcyOS0xNC45ODctMzIuMDY4LTguNzk5LTM0LjE5Mi04LjA5N2wtLjM1OS4xOTRsLTEuOC4zMzVsLS45MjItLjE5MWMtMi41NDItLjUyOC01LjM2Ni0uODItOC4zOTMtLjg2OWMtNC43NTYtLjA4LTguNTkzIDEuMDQ0LTExLjczOSAzLjQzMWwtMi4xODMgMS42NTVsLTIuNTMzLTEuMDQzYy01LjQxMi0yLjIxMy0yMS4zMDgtNi42NjItMjkuNjk2LS43MjFjLTQuNjU2IDMuMjk4LTYuNzc3IDkuNzYtNi4zMDUgMTkuMjA3Yy4xNTYgMy4xMTkgMi4yNzUgMTQuOTI2IDUuNzcxIDI2LjM3N2M0LjgzMSAxNS44MjUgOS4yMjEgMjEuMDgyIDExLjA1NCAyMS42OTNjLjMyLjEwOCAxLjE1LS41MzcgMS45NzYtMS41MjlhMjcxIDI3MSAwIDAgMSAxMC42OTQtMTIuMDdsMi43Ny0yLjkxNWwzLjM0OSAyLjIyNWMxLjM1Ljg5NyAyLjgzOSAxLjQwNiA0LjM2OCAxLjUwMmw3Ljk4Ny02LjgxMmwtMS4xNTcgMTEuODA4Yy0uMDI2LjI2NS0uMDM5LjYyNi4wNjUgMS4yOTZsLjM0OCAyLjIzOGwtMS41MSAxLjY4OGwtLjE3NC4xOTZsNC4zODggMi4wMjV6Ii8+PHBhdGggZmlsbD0iIzMzNjc5MSIgZD0iTTExNS43MzEgNzcuNDRjLTEzLjkyNSAyLjg3My0xNC44ODItMS44NDItMTQuODgyLTEuODQyYzE0LjcwMy0yMS44MTYgMjAuODQ5LTQ5LjUxIDE1LjU0NS01Ni4yODdDMTAxLjkyNC44MjMgNzYuODc1IDkuNTY2IDc2LjQ1NyA5Ljc5M2wtLjEzNS4wMjRjLTIuNzUxLS41NzEtNS44My0uOTExLTkuMjkxLS45NjdjLTYuMzAxLS4xMDMtMTEuMDggMS42NTItMTQuNzA3IDQuNDAyYzAgMC00NC42ODQtMTguNDA4LTQyLjYwNiAyMy4xNTFjLjQ0MiA4Ljg0MiAxMi42NzIgNjYuODk5IDI3LjI2IDQ5LjM2M2M1LjMzMi02LjQxMiAxMC40ODMtMTEuODM0IDEwLjQ4My0xMS44MzRjMi41NTkgMS42OTkgNS42MjIgMi41NjcgOC44MzMgMi4yNTVsLjI1LS4yMTJjLS4wNzguNzk2LS4wNDIgMS41NzUuMSAyLjQ5N2MtMy43NTggNC4xOTktMi42NTQgNC45MzYtMTAuMTY3IDYuNDgyYy03LjYwMiAxLjU2Ni0zLjEzNiA0LjM1NS0uMjIgNS4wODRjMy41MzQuODg0IDExLjcxMiAyLjEzNiAxNy4yMzctNS41OThsLS4yMjEuODgyYzEuNDczIDEuMTggMi41MDcgNy42NzIgMi4zMzQgMTMuNTU3cy0uMjkgOS45MjYuODcxIDEzLjA4MmMxLjE2IDMuMTU2IDIuMzE2IDEwLjI1NiAxMi4xOTIgOC4xNGM4LjI1Mi0xLjc2OCAxMi41MjgtNi4zNTEgMTMuMTI0LTEzLjk5NWMuNDIyLTUuNDM1IDEuMzc3LTQuNjMxIDEuNDM4LTkuNDlsLjc2Ny0yLjNjLjg4NC03LjM2Ny4xNC05Ljc0MyA1LjIyNS04LjYzOGwxLjIzNS4xMDhjMy43NDIuMTcgOC42MzktLjYwMiAxMS41MTQtMS45MzhjNi4xOS0yLjg3MSA5Ljg2MS03LjY2NyAzLjc1OC02LjQwOCIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik03NS45NTcgMTIyLjMwN2MtOC4yMzIgMC0xMC44NC02LjUxOS0xMS45MDctOS4xODVjLTEuNTYyLTMuOTA3LTEuODk5LTE5LjA2OS0xLjU1MS0zMS41MDNhMS41OSAxLjU5IDAgMCAxIDEuNjQtMS41NWExLjU5NCAxLjU5NCAwIDAgMSAxLjU1IDEuNjM5Yy0uNDAxIDE0LjM0MS4xNjggMjcuMzM3IDEuMzI0IDMwLjIyOWMxLjgwNCA0LjUwOSA0LjU0IDguNDUzIDEyLjI3NSA2Ljc5NmM3LjM0My0xLjU3NSAxMC4wOTMtNC4zNTkgMTEuMzE4LTExLjQ2Yy45NC01LjQ0OSAyLjc5OS0yMC45NTEgMy4wMjgtMjQuMDFhMS41OTMgMS41OTMgMCAwIDEgMS43MS0xLjQ3MmExLjU5NyAxLjU5NyAwIDAgMSAxLjQ3MiAxLjcxYy0uMjM5IDMuMTg1LTIuMDg5IDE4LjY1Ny0zLjA2NSAyNC4zMTVjLTEuNDQ2IDguMzg3LTUuMTg1IDEyLjE5MS0xMy43OTQgMTQuMDM3Yy0xLjQ2My4zMTMtMi43OTIuNDUzLTQgLjQ1NE0zMS4zMjEgOTAuNDY2YTYuNyA2LjcgMCAwIDEtMi4xMTYtLjM1Yy01LjM0Ny0xLjc4NC0xMC40NC0xMC40OTItMTUuMTM4LTI1Ljg4NWMtMy41NzYtMTEuNzE3LTUuODQyLTIzLjk0Ny02LjA0MS0yNy45MjJjLS41ODktMTEuNzg0IDIuNDQ1LTIwLjEyMSA5LjAyLTI0Ljc3OGMxMy4wMDctOS4yMTYgMzQuODg4LS40NCAzNS44MTMtLjA2MmExLjU5NiAxLjU5NiAwIDAgMS0xLjIwNyAyLjk1NWMtLjIxMS0uMDg2LTIxLjE5My04LjQ5Mi0zMi43NjgtLjI4NWMtNS42MjIgMy45ODYtOC4yMDMgMTEuMzkyLTcuNjcyIDIyLjAxMWMuMTY3IDMuMzQ5IDIuMjg0IDE1LjI4NSA1LjkwNiAyNy4xNDljNC4xOTQgMTMuNzQyIDguOTY3IDIyLjQxMyAxMy4wOTYgMjMuNzljLjY0OC4yMTYgMi42Mi44NzMgNS40MzktMi41MTdBMjQ1IDI0NSAwIDAgMSA0NS44OCA3My4wNDZhMS41OTYgMS41OTYgMCAwIDEgMi4zMDQgMi4yMDhjLS4wNDguMDUtNC44NDcgNS4wNjctMTAuMDc3IDExLjM1OWMtMi40NzcgMi45NzktNC44NTEgMy44NTMtNi43ODYgMy44NTNtNjkuNDI5LTEzLjQ0NWExLjU5NiAxLjU5NiAwIDAgMS0xLjMyMi0yLjQ4N2MxNC44NjMtMjIuMDU1IDIwLjA4LTQ4LjcwNCAxNS42MTItNTQuNDE0Yy01LjYyNC03LjE4Ni0xMy41NjUtMTAuOTM5LTIzLjYwNC0xMS4xNTZjLTcuNDMzLS4xNi0xMy4zNDEgMS43MzgtMTQuMzA3IDIuMDY5bC0uMjQzLjA5OWMtLjk3MS4zMDUtMS43MTYtLjIyNy0xLjk5Ny0uODQ5YTEuNiAxLjYgMCAwIDEgLjYzMS0yLjAyNWMuMDQ2LS4wMjcuMTkyLS4wODkuNDI5LS4xNzZsLS4wMjEuMDA2bC4wMjEtLjAwN2MxLjY0MS0uNjAxIDcuNjM5LTIuNCAxNS4wNjgtMi4zMTVjMTEuMTA4LjExOCAyMC4yODQgNC40MDEgMjYuNTM0IDEyLjM4OGMyLjk1NyAzLjc3OSAyLjk2NCAxMi40ODUuMDE5IDIzLjg4N2MtMy4wMDIgMTEuNjI1LTguNjUxIDI0LjExOC0xNS40OTcgMzQuMjc3Yy0uMzA2LjQ1Ny0uODEuNzAzLTEuMzIzLjcwM20uNzYgMTAuMjFjLTIuNTM4IDAtNC44MTMtLjM1OC02LjE3NS0xLjE3NGMtMS40LS44MzktMS42NjctMS45NzktMS43MDItMi41ODRjLS4zODItNi43MSAzLjMyLTcuODc4IDUuMjA4LTguNDExYy0uMjYzLS4zOTgtLjYzNy0uODY2LTEuMDI0LTEuMzQ5Yy0xLjEwMS0xLjM3Ni0yLjYwOS0zLjI2LTMuNzcxLTYuMDc4Yy0uMTgyLS40NC0uNzUyLTEuNDYzLTEuNDEyLTIuNjQ4Yy0zLjU3OS02LjQxOC0xMS4wMjYtMTkuNzczLTYuMjQyLTI2LjYxMmMyLjIxNC0zLjE2NSA2LjYyMy00LjQxMSAxMy4xMTktMy43MTZDOTcuNiAyOC44MzcgODguNSAxMC42MjUgNjYuOTA3IDEwLjI3MWMtNi40OTQtLjEwOC0xMS44MiAxLjg4OS0xNS44MjIgNS45M2MtOC45NiA5LjA0OS04LjYzNiAyNS40MjItOC42MzEgMjUuNTg2YTEuNTk1IDEuNTk1IDAgMSAxLTMuMTkuMDg0Yy0uMDItLjcyNy0uMzU0LTE3LjkwOSA5LjU1NC0yNy45MTZDNTMuNDU1IDkuMjcyIDU5LjU1OSA2Ljk2IDY2Ljk2IDcuMDgxYzEzLjgxNC4yMjcgMjIuNzA2IDcuMjUgMjcuNzMyIDEzLjEwMWM1LjQ3OSA2LjM3NyA4LjE2NSAxMy40MTEgOC4zODYgMTUuNzU5Yy4xNjUgMS43NDYtMS4wODggMi4wOTUtMS4zNDEgMi4xNDdsLS41NzYuMDEzYy02LjM3NS0xLjAyMS0xMC40NjUtLjMxMi0xMi4xNTYgMi4xMDRjLTMuNjM5IDUuMjAxIDMuNDA2IDE3LjgzNCA2LjQxNCAyMy4yMjljLjc2OCAxLjM3NiAxLjMyMiAyLjM3MSAxLjU3NiAyLjk4NWMuOTg4IDIuMzk2IDIuMjc3IDQuMDA2IDMuMzEyIDUuM2MuOTExIDEuMTM4IDEuNyAyLjEyNSAxLjk4MiAzLjI4M2MuMTMxLjIzIDEuOTkgMi45OCAxMy4wMjEuNzAzYzIuNzY1LS41NyA0LjQyMy0uMDgzIDQuOTMgMS40NWMuOTk3IDMuMDE1LTQuNTk3IDYuNTMyLTcuNjk0IDcuOTdjLTIuNzc1IDEuMjktNy4yMDQgMi4xMDYtMTEuMDM2IDIuMTA2bS00LjY5Ni00LjAyMWMuMzUuMzUzIDIuMTAxLjk2MiA1LjcyNy44MDZjMy4yMjQtLjEzOCA2LjYyNC0uODM5IDguNjY0LTEuNzg2YzIuNjA5LTEuMjEyIDQuMzUxLTIuNTY3IDUuMjUzLTMuNDkybC0uNS4wOTJjLTcuMDUzIDEuNDU2LTEyLjA0MiAxLjI2Mi0xNC44MjgtLjU3N2E2IDYgMCAwIDEtLjU0LS40MDFjLS4zMDIuMTE5LS41ODEuMTk3LS43OC4yNTNjLTEuNTguNDQzLTMuMjE0LjkwMi0yLjk5NiA1LjEwNW0tNDUuNTYyIDguOTE1Yy0xLjc1MiAwLTMuNTk2LS4yMzktNS40NzktLjcxYy0xLjk1MS0uNDg4LTUuMjQtMS45NTctNS4xOS00LjM3Yy4wNTctMi43MDcgMy45OTQtMy41MTkgNS40NzYtMy44MjRjNS4zNTQtMS4xMDMgNS43MDMtMS41NDUgNy4zNzYtMy42N2MuNDg4LS42MTkgMS4wOTUtMS4zOSAxLjkyMy0yLjMxNGMxLjIyOS0xLjM3NiAyLjU3Mi0yLjA3MyAzLjk5Mi0yLjA3M2MuOTg5IDAgMS44LjMzNSAyLjMzNi41NThjMS43MDguNzA4IDMuMTMzIDIuNDIgMy43MTkgNC40NjdjLjUyOSAxLjg0Ny4yNzYgMy42MjUtLjcxIDUuMDA2Yy0zLjIzNyA0LjUzMy03Ljg4NiA2LjkzLTEzLjQ0MyA2LjkzbS03LjIyMi00Ljk0M2MuNDgxLjM3MiAxLjQ0NS44NjkgMi41MTggMS4xMzdjMS42MzEuNDA4IDMuMjEzLjYxNSA0LjcwNS42MTVjNC41NDYgMCA4LjE5Ni0xLjg4MiAxMC44NDctNS41OTRjLjU1My0uNzc0LjM4Ny0xLjc1Ny4yMzktMi4yNzRjLS4zMS0xLjA4My0xLjA4LTIuMDY4LTEuODczLTIuMzk3Yy0uNDMtLjE3OC0uNzg3LS4zMTQtMS4xMTUtLjMxNGMtLjE3NiAwLS43MTIgMC0xLjYxNCAxLjAwOWE0MSA0MSAwIDAgMC0xLjc5NCAyLjE2MmMtMi4wODQgMi42NDYtMy4wMzkgMy41NDQtOS4yMzkgNC44MjFjLTEuNTEzLjMxLTIuMjg5LjYyNi0yLjY3NC44MzVtMTIuMjY5LTcuMzZhMS41OTYgMS41OTYgMCAwIDEtMS41NzUtMS4zNTRhOCA4IDAgMCAxLS4wOC0uNzk5Yy00LjA2NC0uMDc2LTcuOTg1LTEuODItMTAuOTYyLTQuOTI2Yy0zLjc2NC0zLjkyNy01LjQ3Ny05LjM2OC00LjY5OS0xNC45MjdjLjg0NS02LjAzNy41MjktMTEuMzY2LjM1OS0xNC4yMjljLS4wNDctLjc5Ni0uMDgxLTEuMzcxLS4wNzktMS43NjljLjAwMy0uNTA1LjAxMy0xLjg0NCA0LjQ4OS00LjExM2MxLjU5Mi0uODA3IDQuNzg0LTIuMjE1IDguMjcxLTIuNTc2YzUuNzc3LS41OTcgOS41ODUgMS45NzYgMTAuNzI1IDcuMjQ2YzMuMDc3IDE0LjIyOC4yNDQgMjAuNTIxLTEuODI1IDI1LjExN2MtLjM4NS44NTYtLjc0OSAxLjY2NC0xLjA0IDIuNDQ3bC0uMjU3LjY5Yy0xLjA5MyAyLjkzMS0yLjAzOCA1LjQ2My0xLjc0OCA3LjM1NGExLjU5NSAxLjU5NSAwIDAgMS0xLjMzNSAxLjgxOXpNNDIuNDY0IDQyLjI2bC4wNjIgMS4xMzljLjE3NiAyLjk3NC41MDQgOC41MDgtLjM4NCAxNC44NmMtLjY0MSA0LjU4NS43NTkgOS4wNiAzLjg0MyAxMi4yNzZjMi40MzcgMi41NDIgNS42NDQgMy45NDUgOC45NCAzLjk0NWguMDY4Yy4zNjktMS41NTUuOTgyLTMuMTk3IDEuNjQyLTQuOTY2bC4yNTUtLjY4NmMuMzI5LS44ODQuNzE0LTEuNzQgMS4xMjItMi42NDZjMS45OTEtNC40MjQgNC40Ny05LjkzMSAxLjYxNS0yMy4xMzJjLS41NjUtMi42MTUtMS45MzYtNC4xMjgtNC4xODktNC42MjdjLTQuNjI4LTEuMDIyLTExLjUyNSAyLjQ1OS0xMi45NzQgMy44MzdtOS42My0uNjc3Yy0uMDguNTY0IDEuMDMzIDIuMDcgMi40ODUgMi4yNzFjMS40NDkuMjAzIDIuNjg5LS45NzUgMi43NjgtMS41MzlzLTEuMDMzLTEuMTg2LTIuNDg1LTEuMzg4cy0yLjY5MS4wOTItMi43NjguNjU2bTIuODE4IDIuODI2bC0uNDA3LS4wMjhjLS45LS4xMjUtMS44MS0uNjkyLTIuNDMzLTEuNTE4Yy0uMjE5LS4yOS0uNTc2LS44NTItLjUwNS0xLjM1NGMuMTAxLS43MzYuOTk5LTEuMTc3IDIuNC0xLjE3N2MuMzEzIDAgLjYzOS4wMjMuOTY3LjA2OWMuNzY2LjEwNiAxLjQ3Ny4zMjcgMi4wMDIuNjJjLjkxLjUwOC45NzcgMS4wNzUuOTM2IDEuMzY4Yy0uMTEyLjgxMy0xLjQwNSAyLjAyLTIuOTYgMi4wMm0tMi4yODktMi43MzJjLjA0NS4zNDguOTA3IDEuNDk2IDIuMDI5IDEuNjUxbC4yNjEuMDE4YzEuMDM2IDAgMS44MS0uODE1IDEuOTAxLTEuMDgyYy0uMDk2LS4xODItLjc2Mi0uNjM0LTIuMDI1LS44MWE2IDYgMCAwIDAtLjgyMS0uMDU5Yy0uODEyIDAtMS4yNDMuMTgzLTEuMzQ1LjI4Mm00My42MDUtMS4yNDVjLjA3OS41NjQtMS4wMzMgMi4wNy0yLjQ4NCAyLjI3MmMtMS40NS4yMDItMi42OTEtLjk3NS0yLjc3MS0xLjUzOWMtLjA3Ni0uNTY0IDEuMDM2LTEuMTg3IDIuNDg2LTEuMzg4YzEuNDUtLjIwMyAyLjY4OS4wOTIgMi43NjkuNjU1bS0yLjgxOSAyLjU2Yy0xLjM5NiAwLTIuNjAxLTEuMDg2LTIuNy0xLjc5MWMtLjExNS0uODQ2IDEuMjc4LTEuNDg5IDIuNzEyLTEuNjg4Yy4zMTYtLjA0NC42MjktLjA2Ni45My0uMDY2YzEuMjM4IDAgMi4wNTguMzYzIDIuMTQuOTQ5Yy4wNTMuMzc5LS4yMzguOTY0LS43MzkgMS40OTJjLS4zMzEuMzQ3LTEuMDI2Ljk0OC0xLjk3MyAxLjA3OXptLjk0My0zLjAxM3EtLjQxNiAwLS44NTYuMDYxYy0xLjQ0MS4yMDEtMi4zMDEuNzc5LTIuMjU5IDEuMDg5Yy4wNDguMzQxLjk2OCAxLjMzMiAyLjE3MyAxLjMzMmwuMjk3LS4wMjFjLjc4Ny0uMTA5IDEuMzc4LS42MjMgMS42Ni0uOTE5Yy40NDMtLjQ2NS42MTktLjkwMy41OTgtMS4wNTJjLS4wMjgtLjE5OC0uNTYtLjQ5LTEuNjEzLS40OW0zLjk2NSAzMi44NDNhMS41OTQgMS41OTQgMCAwIDEtMS4zMjQtMi40ODNjMy4zOTgtNS4wNzUgMi43NzYtMTAuMjUgMi4xNzUtMTUuMjU1Yy0uMjU3LTIuMTMyLS41MjEtNC4zMzctLjQ1My02LjQ1M2MuMDctMi4xNzcuMzQ3LTMuOTczLjYxNC01LjcxYy4zMTctMi4wNTguNjE3LTQuMDAyLjQ5My02LjMxYTEuNTk1IDEuNTk1IDAgMSAxIDMuMTg2LS4xNzJjLjE0MiAyLjYzOC0uMTk3IDQuODM4LS41MjUgNi45NjdjLS4yNTMgMS42NDMtLjUxNSAzLjM0Mi0uNTc4IDUuMzI3Yy0uMDYxIDEuODc0LjE3OCAzLjg2NC40MzEgNS45N2MuNjQgNS4zMjIgMS4zNjUgMTEuMzU0LTIuNjkxIDE3LjQxMWExLjYgMS42IDAgMCAxLTEuMzI4LjcwOCIvPjwvc3ZnPg==" width="32" height="32" x="1156.290433969414" y="-17.703708685546587" >
                    <animate attributeName="x" values="1156.290433969414;1273.2766423557532" dur="10s" repeatCount="indefinite" begin="8.2s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="8.2s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="8.2s"/>
            </g>

    <image
            href="data:image/png;base64,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"
            x="655.5" y="86"
            width="130" height="130"
            clip-path="url(#avatarClip)"
            preserveAspectRatio="xMidYMid slice" />

    <circle cx="720.5" cy="151" r="65"
            fill="none"
            stroke="url(#glowGrad)"
            stroke-width="3"
            filter="url(#glow)">
        <animate attributeName="r"
                 values="60;70;60"
                 dur="2.5s"
                 repeatCount="indefinite"/>
        <animate attributeName="opacity"
                 values="0.6;1;0.6"
                 dur="2.5s"
                 repeatCount="indefinite"/>
    </circle>

    <g transform="translate(720.5 151)">
        <circle cx="0" cy="0" r="80"
                fill="none"
                stroke="url(#glowGrad)"
                stroke-width="2"
                stroke-dasharray="6 4"
                filter="url(#glow)">
            <animateTransform
                    attributeName="transform"
                    type="rotate"
                    from="0"
                    to="360"
                    dur="10s"
                    repeatCount="indefinite"/>
        </circle>
    </g>

    <!-- Floating particles -->
    <g fill="#8a81fd" opacity="0.8">
        
        <circle cx="144" cy="242" r="2">
            <animate attributeName="cy" values="242;60" dur="5s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/>
        </circle>
        <circle cx="389" cy="76" r="2">
            <animate attributeName="cy" values="76;272" dur="6s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="6s" repeatCount="indefinite"/>
        </circle>
        <circle cx="144" cy="242" r="2">
            <animate attributeName="cy" values="242;60" dur="7s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="7s" repeatCount="indefinite"/>
        </circle>
        <circle cx="775" cy="76" r="2">
            <animate attributeName="cy" values="76;272" dur="5s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/>
        </circle>
        <circle cx="492" cy="242" r="2">
            <animate attributeName="cy" values="242;60" dur="6s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="6s" repeatCount="indefinite"/>
        </circle>
        <circle cx="773" cy="76" r="2">
            <animate attributeName="cy" values="76;272" dur="7s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="7s" repeatCount="indefinite"/>
        </circle>
        <circle cx="1124" cy="242" r="2">
            <animate attributeName="cy" values="242;60" dur="5s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/>
        </circle>
        <circle cx="800" cy="76" r="2">
            <animate attributeName="cy" values="76;272" dur="6s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="6s" repeatCount="indefinite"/>
        </circle>
        <circle cx="1297" cy="242" r="2">
            <animate attributeName="cy" values="242;60" dur="7s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="7s" repeatCount="indefinite"/>
        </circle>
        <circle cx="1229" cy="76" r="2">
            <animate attributeName="cy" values="76;272" dur="5s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/>
        </circle>
    </g>

    
</svg>

##  Quem Sou Eu

- Atualmente cursando Ciência da Computação na Universidade Federal do Pará (1/8)  
- 2008, 18y  


## Tech Stack

<p align="center">
  <img src="https://cdn.simpleicons.org/javascript/F7DF1E" width="40" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/node.js/339933" width="40" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/n8n/EA4B71" width="40" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/postgresql/4169E1" width="40" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/supabase/3ECF8E" width="40" />
</p>


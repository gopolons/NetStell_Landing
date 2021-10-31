<template>

<div class="container-fluid">
        <div class="row pt-5">
            <div class="col-10 pl-0 text-right">
                <h1 class="background-secondary pr-5 pt-2 pb-2 color-white">НАПРАВЛЕНИЯ КОМПАНИИ</h1>
            </div>

        </div>

        <div class="position-relative">
            <div class="row pt-5 hexagons1">
                <svg class="" width="300" height="300" viewBox="0 0 540 584" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5 434.896V148.94L270 5.68383L535 148.94V434.896L270 578.152L5 434.896Z" fill="white" stroke="url(#paint0_linear_122:145)" stroke-width="10"/>
                    <defs>
                        <linearGradient id="paint0_linear_122:145" x1="-94" y1="-83" x2="455.5" y2="525" gradientUnits="userSpaceOnUse">
                            <stop stop-color="#4E4E4E"/>
                        </linearGradient>
                    </defs>
                </svg>
                <svg class="" width="300" height="300" viewBox="0 0 540 584" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5 434.896V148.94L270 5.68383L535 148.94V434.896L270 578.152L5 434.896Z" fill="white" stroke="url(#paint0_linear_122:145)" stroke-width="10"/>
                    <defs>
                        <linearGradient id="paint0_linear_122:145" x1="-94" y1="-83" x2="455.5" y2="525" gradientUnits="userSpaceOnUse">
                            <stop stop-color="#4E4E4E"/>
                        </linearGradient>
                    </defs>
                </svg>
                <svg class="" width="300" height="300" viewBox="0 0 540 584" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5 434.896V148.94L270 5.68383L535 148.94V434.896L270 578.152L5 434.896Z" fill="white" stroke="url(#paint0_linear_122:145)" stroke-width="10"/>
                    <defs>
                        <linearGradient id="paint0_linear_122:145" x1="-94" y1="-83" x2="455.5" y2="525" gradientUnits="userSpaceOnUse">
                            <stop stop-color="#4E4E4E"/>
                        </linearGradient>
                    </defs>
                </svg>
            </div>
            
            <div class="row hexagons2">
                <svg class="" width="300" height="300" viewBox="0 0 540 584" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5 434.896V148.94L270 5.68383L535 148.94V434.896L270 578.152L5 434.896Z" fill="white" stroke="url(#paint0_linear_122:145)" stroke-width="10"/>
                    <defs>
                        <linearGradient id="paint0_linear_122:145" x1="-94" y1="-83" x2="455.5" y2="525" gradientUnits="userSpaceOnUse">
                            <stop stop-color="#4E4E4E"/>
                        </linearGradient>
                    </defs>
                </svg>
                <svg class="" width="300" height="300" viewBox="0 0 540 584" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5 434.896V148.94L270 5.68383L535 148.94V434.896L270 578.152L5 434.896Z" fill="white" stroke="url(#paint0_linear_122:145)" stroke-width="10"/>
                    <defs>
                        <linearGradient id="paint0_linear_122:145" x1="-94" y1="-83" x2="455.5" y2="525" gradientUnits="userSpaceOnUse">
                            <stop stop-color="#4E4E4E"/>
                        </linearGradient>
                    </defs>
                </svg>
            </div>
        </div>
    </div>

</template>

<script>
export default {
    name: 'HomeDirections'
}
</script>

<style scoped>

.background-secondary {
    background-color: #18D1FF;
}

.color-white {
    color: white;
}

.hexagons1 {
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, 0%) 
}
.hexagons2 {
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, 100%) 
}

.masked {
    mask-image: url('/assets/hexagon.svg');
}

</style>
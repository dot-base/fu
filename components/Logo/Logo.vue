<template>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 53 67" :width="width">
        <g clip-path="url(#a)">
            <mask id="b" width="53" height="67" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type: luminance">
                <path fill="#fff" d="M53 0H0v67h53V0Z" />
            </mask>
            <g fill="#1D1D1B" mask="url(#b)">
                <path
                    d="M13.34 33.57c0 3.677-3.002 6.685-6.67 6.685S0 37.247 0 33.57c0-3.677 3.001-6.686 6.67-6.686 3.668 0 6.669 3.009 6.669 6.686M13.34 46.941c0 3.677-3.002 6.686-6.67 6.686S0 50.62 0 46.941s3.001-6.686 6.67-6.686c3.668 0 6.669 3.01 6.669 6.686"
                />
                <path
                    d="M26.56 33.57c0 3.677-3.002 6.685-6.67 6.685s-6.67-3.008-6.67-6.685c0-3.677 3.002-6.686 6.67-6.686s6.67 3.009 6.67 6.686ZM26.56 20.166c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686 6.67 3.01 6.67 6.686ZM26.56 46.941c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686 6.67 3.01 6.67 6.686ZM26.56 60.314c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686 6.67 3.009 6.67 6.686Z"
                />
                <path
                    d="M39.78 33.57c0 3.677-3.002 6.685-6.67 6.685s-6.67-3.008-6.67-6.685c0-3.677 3.002-6.686 6.67-6.686s6.67 3.009 6.67 6.686ZM39.78 20.166c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686 6.67 3.01 6.67 6.686ZM39.78 46.941c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686 6.67 3.01 6.67 6.686ZM39.78 60.314c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686 6.67 3.009 6.67 6.686Z"
                />
                <path
                    d="M53 33.57c0 3.677-3.002 6.685-6.67 6.685s-6.67-3.008-6.67-6.685c0-3.677 3.002-6.686 6.67-6.686C50 26.884 53 29.893 53 33.57ZM53 6.686c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686S42.663 0 46.33 0C50 0 53 3.009 53 6.686ZM53 46.941c0 3.677-3.002 6.686-6.67 6.686s-6.67-3.009-6.67-6.686 3.002-6.686 6.67-6.686c3.669 0 6.67 3.01 6.67 6.686Z"
                />
            </g>
        </g>
        <defs>
            <clipPath id="a"><path fill="#fff" d="M0 0h53v67H0z" /></clipPath>
        </defs>
    </svg>
</template>

<script setup lang="ts">
interface Props {
    width?: string;
}

defineProps<Props>();
</script>

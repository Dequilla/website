<script>

</script>

<div class="animate-flicker">
    <p>Scroll down</p>
    <i class="fas fa-chevron-down"></i>
</div>

<style>
    div {
        margin: 20px;
        font-size: 1.2em;
        margin: 20px;
    }

    p {
        font-weight: 700;
    }

    i {
        display: block;
        font-size: 1.2em;
        margin-top: 6px;
    }

    @keyframes flickerAnimation {
        0%   { opacity:1; }
        25%   { opacity:1; }
        50%  { opacity:0; }
        75% { opacity:1; }
        100% { opacity:1; }
    }

    @-o-keyframes flickerAnimation{
        0%   { opacity:1; }
        25%   { opacity:1; }
        50%  { opacity:0; }
        75% { opacity:1; }
        100% { opacity:1; }
    }

    @-moz-keyframes flickerAnimation{
        0%   { opacity:1; }
        25%   { opacity:1; }
        50%  { opacity:0; }
        75% { opacity:1; }
        100% { opacity:1; }
    }

    @-webkit-keyframes flickerAnimation{
        0%   { opacity:1; }
        25%   { opacity:1; }
        50%  { opacity:0; }
        75% { opacity:1; }
        100% { opacity:1; }
    }

    .animate-flicker {
        -webkit-animation: flickerAnimation 5s infinite;
        -moz-animation: flickerAnimation 5s infinite;
        -o-animation: flickerAnimation 5s infinite;
        animation: flickerAnimation 5s infinite;
    }

</style>

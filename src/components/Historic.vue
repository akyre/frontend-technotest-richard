<template>
<div class="history">
    <div class="left">
        <div class="blue-box">
            <div>
                <div>
                    <div class="ThirtySize robotoMediumItalic">{{ First_Name }} - {{ Job }}</div>
                    <div style="display: flex; margin-top: 5px;"><div class="robotoThinItalic TwentyFiveSize">{{ Meeting_Date }}</div> <div style="margin-left: 6px" class="robotoMediumItalic TwentyFiveSize"> - {{ Meeting_Hour }}</div></div>
                </div>
                <div class="insight-ctn">
                    <div class="insight robotoThinItalic">
                        <img src="../assets/stars.png">
                        {{ Rating }} avis
                    </div>
                </div>
            </div>
            <div class="message">
                <img src="../assets/enveloppe.svg">
            </div>
        </div>
        <div class="comment">
            <div class="robotoLightItalic ThirtySize">Commentaire:</div>
            <div class="comment-content robotoLightItalic TwentyFourSize">
                {{ Commentary }}
            </div>
        </div>
    </div>
    <div class="right">
        <div>
            <video class="history-video" width="450px" controls>
                <source src="{history.video}" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
    </div>
</div>
    
</template>

<script>
export default {
  name: 'Historic',
  props: ['Commentary', 'First_Name', 'Job', 'Meeting_Date', 'Rating', 'Meeting_Hour']
}

</script>

<style>
    .history {
        display: inline-flex;
        padding: 15px;
        border-radius: 5px;
        -webkit-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        -moz-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        margin: 50px 0;
        width: 80%;
    }

    .blue-box {
        background-color: #6689E6;
        border-radius: 5px;
        padding: 10px;
        display: flex;
        margin: 20px;
        color: #F3F3F3;
        -webkit-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        -moz-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
    }

    .history-video {
        outline: none;
        border-radius: 5px;
        margin: 20px;
        -webkit-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        -moz-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
    }

    .comment {
        -webkit-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        -moz-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        border-radius: 5px;
        margin: 20px;
        padding: 10px;
    }

    .message {
        display: flex;
        justify-content: flex-end;
        flex-grow: 1;
        align-items: flex-end;
    }

    .stars {
        display: flex;
        justify-content: flex-start;
        flex-grow: 1;
        align-items: flex-end;
    }

    .checked {
        color: #FFE27B!important;
    }

    .insight-ctn {
        margin-top: 20px;
        display: flex;
        align-items: center;
    }

    .insight {
        font-size: 20px;
        margin-left: 10px;
    }

    .robotoMediumItalic {
        font-family: "Roboto", sans-serif;
        font-weight: 400;
        font-style: italic;
    }

    .robotoThinItalic {
        font-family: "Roboto", sans-serif;
        font-weight: lighter;
        font-style: italic;
    }

    .robotoLightItalic {
        font-family: "Roboto", sans-serif;
        font-weight: 300;
        font-style: italic;
    }

    .ThirtySize {
        font-size: 30px;
    }

    .TwentyFourSize {
        font-size: 24px;
    }

    .TwentyFiveSize {
        font-size: 25px;
    }

</style>


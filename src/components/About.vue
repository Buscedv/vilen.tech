<template>
    <div class="row">
        <div class="col-xs-1 col-md-2 col-lg-3">
        </div>
        <div class="col-xs-10 col-md-8 col-lg-6 card">
            <div class="content">
                <h1 class="section-title">About me</h1>
                <h2>Full Stack Software Developer at PHZ Full Stack</h2>
                <h3>I'm a highly motivated software developer who is getting his footing the industry. <br><br>
                    With my experience in many different projects and a diverse job description, I am able to
                    quickly learn and
                    adapt to new challenges and become a jack of all trades. May it be front- and backend
                    development, devops,
                    cloud technologies or digital marketing. <br><br>
                    New challenges attract me and lead to my personal professional growth. I am able to work well
                    both in agile
                    team environment and independently. <br><br>
                    On my free time I enjoy diversity of sports, such as skiing, jogging, gym, frisbee golf and
                    motorsports.
                </h3>
            </div>
        </div>
        <div class="col-xs-1 col-md-2 col-lg-3">
        </div>
    </div>
</template>

<script>
export default {
    name: 'About',
}
</script>

<style scoped>

.card {
    height: 40rem;
    border-radius: 70px;
    background-color: rgba(255, 255, 255, 0.73);
    box-shadow: -.1rem 0 3rem #777676;
}

.content {
    margin-top: 10%;
    padding-left: 50px;
    padding-right: 50px;
}

.section-title {
    font-size: 5rem;
    margin: 0 auto;
    text-align: center;
    color: var(--text-light);
    -webkit-text-stroke: 2px black;
}

@media screen and (max-width: 600px) {
    .section-title {
        font-size: 2rem;
        -webkit-text-stroke: 1px black;
    }

    .card {
        height: 34rem
    }

    .content {
        font-size: 11px;
        margin-top: 0;
    }
}
</style>
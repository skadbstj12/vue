<template>
    <section id="intro">
        <div class="intro__inner">
            <h2 class="intro__title">develop port</h2>
            <div class="intro__lines" aria-hidden="true">
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
            </div>
            <div class="intro__text">
                <div class="text">
                    <div>talent is</div>
                    <div>found at the end of the</div>
                    <div>effort</div>
                </div>
                <div class="img">
                    <img src="https://images.unsplash.com/photo-1595956553066-fe24a8c33395?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                </div>
            </div>
            <div class="intro__lines bottom" aria-hidden="true">
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    #intro{
        height: 100vh;

        .intro__inner{
            width: 100%;
            height: 100%;
            display: flex;
            align-items: flex-start;
            justify-content: flex-end;
            flex-direction: column;
            padding: 16px;

            .intro__title {
                color: #96b4d1;
                margin: 0 auto;
                font-size: 10vw;
                line-height: 1;
                font-weight: 800;
                white-space: nowrap;
                text-transform: uppercase;
                letter-spacing: -0.3vw;
            }

            .intro__lines {
                    width: 100%;

            .line {
                display: block;
                width: 100%;
                height: 1px;
                background-color: var(--black);
                margin-bottom: 0.2vw;
                box-shadow: 0 20px 20px  #000000;

                &:nth-child(1) {
                    height: 0;
                    
                }

                &:nth-child(2) {
                    height: 0;
                }

                &:nth-child(3) {
                  height: 0;
                }

                &:nth-child(4) {
                    background-color: rgba(24, 24, 24, 0.35);
                    backdrop-filter: blur(1px);
                    height: 8px;
                    margin: 0 auto;
                    border-radius: 120px 120px 0 0;
                    width: 93.3%;
                }

                &:nth-child(5) {
                    background-color: rgba(24, 24, 24, 0.4);
                    backdrop-filter: blur(1px);
                    height: 12px;
                    margin: 0 auto;
                    border-radius: 120px 120px 0 0;
                    width: 94.7%;
                }

                &:nth-child(6) {
                    background-color: rgba(24, 24, 24, 0.5);
                    backdrop-filter: blur(1px);
                    height: 14px;
                    margin: 0.02rem auto;
                    border-radius: 100px 100px 0 0;
                    width: 96.1%;
                }

                &:nth-child(7) {
                background-color: rgba(24, 24, 24, 0.65);
                backdrop-filter: blur(5px);
                height: 18px;
                margin: 0 auto;
                width: 98.3%;
                border-radius: 30px 30px 0 0;
                }
            }
            &.bottom {
                        display: none;
                    }
        }


            
            .intro__text{
                border-radius: 15px 15px 15px 15px;
                width: 100%;
                height: 40vh;
                background-color: var(--black);
                color: var(--white);
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: column;
                position: relative;

                .text{
                    font-size: 3vw;
                    line-height: 1;
                    font-weight: 900;
                    text-transform: uppercase;
                    text-decoration: underline;
                    text-align: center;
                    position: relative;
                    z-index: 100;
                    transition: all 0.3s;
                    cursor: all-scroll;
                }

                .img{
                    position: absolute;
                    left: 50%;
                    top: 50%;
                    transform: translate(-50%, -50%);
                    width: 30vh;
                    height: 30vh;
                    border-radius: 50%;
                    overflow: hidden;
                    filter: grayscale(100%);
                    transition: all 0.3s;
                    object-position: 10px;
                }
            }
        }

    }
</style>
<template>
    <div>
        <div class="my-5">
            <div class="text-center my-5 ">
                <img src="../assets/img/logo.png" alt="">
            </div>

            <div class="d-flex flex-row justify-content-around">
                <div class="d-flex flex-column">
                    <div><b>Overview</b></div>
                    <div>Shipping</div>
                    <div>Refund</div>
                    <div>Promotion</div>
                </div>
                <div>
                    <div><b>Company</b></div>
                    <div>About</div>
                    <div>Career</div>
                    <div>Contact Us</div>
                </div>
                <div>
                    <div><b>Explore</b></div>
                    <div>Terms & Condition</div>
                    <div>Privacy Podivcy</div>
                    <div>For Developer</div>
                </div>
                <div>
                    <h5><b>Space Letter</b> </h5>
                    <form class="d-flex" id="form-email">
                        <input class="form-control mr-sm-2" type="email" placeholder="your email address"
                            aria-label="Search" id="email" name="email">
                        <button class="btn btn-outline-success my-2 my-sm-0" id="btnAlert" type="submit"><img
                                src="../assets/img/tele-icon.png" alt="icon" style="background-color: pink;"></button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'footerCmp',
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
  
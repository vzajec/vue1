<template>

      <div class="card">
        <div class="card-header text-left">
          <img alt="Slika profila cvjecarnicairis" class="slikaprofila" src="https://instagram.fzag1-1.fna.fbcdn.net/vp/d0a7e067d403fcf5422564750b5fc776/5E79382E/t51.2885-19/s150x150/70841172_386342385633262_504758352060874752_n.jpg?_nc_ht=instagram.fzag1-1.fna.fbcdn.net">
          <a class="imekorisnika" href="/">pero_peric</a>
        </div>
        <div class="card-body p-0">
          <img class="card-img-top" src="/gold-tooth.jpg" alt="Covjek sa zlatnim zubima">
        </div>
        <div class="card-footer text-muted text-left">
          <section class="sH9wk  _JgwE "><div class="RxpZH"><form class="X7cDz" method="POST"><textarea aria-label="Komentiraj..." placeholder="Komentiraj..." class="Ypffh" autocomplete="off" autocorrect="off"></textarea><button class="sqdOP yWX7d    y3zKF     " disabled="" type="submit">Objavi</button></form></div></section>
        
      </div>
      </div>
</template>

<script>
export default {
  name: 'InstagramCard',
  props: {
    msg: String
  }
}
</script>

<style>
.imekorisnika {
    font-weight: 600;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    padding-left: 5px;
    color:#262626;
    color: rgba(var(--i1d,38,38,38),1);
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    font-size: 14px;
    line-height: 18px;
}
    



.slikaprofila{
  border-radius: 50%;
  height: 30px;
}

.X7cDz {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-flex-shrink: 1;
    -ms-flex-negative: 1;
    flex-shrink: 1;
    position: relative;
}
.X7cDz, .Ypffh {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-flex: 1;
    -webkit-flex-grow: 1;
    -ms-flex-positive: 1;
    flex-grow: 1;
}
.X7cDz, .n1LTb .RxpZH {
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
}


body, button, input, textarea {
    color: #262626;
    color: rgba(var(--i1d,38,38,38),1);
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    font-size: 14px;
    line-height: 18px;
}



.sqdOP {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background: 0 0;
    border: 0;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    cursor: pointer;
    display: block;
    font-weight: 600;
    padding: 5px 9px;
    text-align: center;
    text-transform: inherit;
    text-overflow: ellipsis;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    width: auto;
}

.Ypffh {
    background: 0 0;
    border: 0;
    color: 
    #262626;
    font-size: inherit;
    height: 18px;
    max-height: 80px;
    outline: 0;
    padding: 0;
    resize: none;
}
.X7cDz, .Ypffh {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-flex: 1;
    -webkit-flex-grow: 1;
    -ms-flex-positive: 1;
    flex-grow: 1;
}












</style>
<script setup>


const users = [
    {
      userPhoto: "/src/assets/Ellipse%202.svg",
      userName: "Salvador Stewart Flynn Thomas Salva Salve...",
      userWho: "Leading specialist of the department of cent...",
      userMail: "frontend_develop@gmail.com",
      userPhone: "+38 (098) 278 44 24"

    },

  {
    userPhoto: "/src/assets/Ellipse%203.svg",
    userName: "Takamaru Ayako Jurrien",
    userWho: "Lead Independent Director",
    userMail: "Takamuru@gmail.com",
    userPhone: "+38 (098) 278 90 2"

  },

  {
    userPhoto: "/src/assets/Ellipse%204.svg",
    userName: "Ilya",
    userWho: "Co-Founder and CEO",
    userMail: "Ilya_founder@gmail.com",
    userPhone: "+38 (098) 235 44 24"

  },

  {
    userPhoto: "/src/assets/Ellipse%205.svg",
    userName: "Alexandre",
    userWho: "Lead Independent Director",
    userMail: "Alexandr_develop@gmail.com",
    userPhone: "+38 (098) 198 44 24"

  },

  {
    userPhoto: "/src/assets/Ellipse%206.svg",
    userName: "Winny",
    userWho: "Former Senior Director",
    userMail: "Winny_develop@gmail.com",
    userPhone: "+38 (098) 278 22 88"

  },

  {
    userPhoto: "/src/assets/Ellipse%201.svg",
    userName: "Simon",
    userWho: "President of Commerce",
    userMail: "Simon@gmail.com",
    userPhone: "+38 (098) 278 44 00"

  }
]
</script>

<template>

  <div class="cards">
    <div class="cards__container">
    <ul class="card_items">
      <li class="card-item">
        <div class="card-content">
          <img class="card-image" src="/src/assets/Ellipse%202.svg" alt="Chel_1">
          <p title="Salvador Stewart Flynn Thomas Salva Salve" class="team-member-name">Salvador Stewart Flynn Thomas Salva Salve</p>
          <p class="team-member-who">Leading specialist of the department of cent...</p>
          <p title="frontend_develop@gmail.com" class="team-member-mail">frontend_develop@gmail.com</p>
          <p class="team-member-phone">+38 (098) 278 44 24</p>
        </div>
      </li>
      <li class="card-item">
        <div class="card-content">
          <img class="card-image" src="/src/assets/Ellipse%203.svg" alt="Chel_2">
          <p title="Takamaru Ayako Jurrien" class="team-member-name">Takamaru Ayako Jurrien</p>
          <p class="team-member-who">Lead Independent Director</p>
          <p class="team-member-mail">Takamuru@gmail.com</p>
          <p class="team-member-phone">+38 (098) 278 90 2</p>
        </div>
      </li>
      <li class="card-item">
        <div class="card-content">
          <img class="card-image" src="/src/assets/Ellipse%204.svg" alt="Chel_3">
          <p title="Ilya" class="team-member-name">Ilya</p>
          <p class="team-member-who">Co-Founder and CEO</p>
          <p class="team-member-mail">Ilya_founder@gmail.com</p>
          <p class="team-member-phone">+38 (098) 235 44 24</p>
        </div>
      </li>
      <li class="card-item">
        <div class="card-content">
          <img class="card-image" src="/src/assets/Ellipse%205.svg" alt="Chel_4">
          <p title="Alexandre" class="team-member-name">Alexandre</p>
          <p class="team-member-who">Lead Independent Director</p>
          <p class="team-member-mail">Alexandr_develop@gmail.com</p>
          <p class="team-member-phone">+38 (098) 198 44 24</p>
        </div>
      </li>
      <li class="card-item">
        <div class="card-content">
          <img class="card-image" src="/src/assets/Ellipse%206.svg" alt="Chel_5">
          <p title="Winny" class="team-member-name">Winny</p>
          <p class="team-member-who">Former Senior Director</p>
          <p class="team-member-mail">Winny_develop@gmail.com</p>
          <p class="team-member-phone">+38 (098) 278 22 88</p>
        </div>
      </li>
      <li class="card-item">
        <div class="card-content">
          <img class="card-image" src="/src/assets/Ellipse%201.svg" alt="Chel_6">
          <p title="Simon" class="team-member-name">Simon</p>
          <p class="team-member-who">President of Commerce</p>
          <p class="team-member-mail">Simon@gmail.com</p>
          <p class="team-member-phone">+38 (098) 278 44 00</p>
        </div>
      </li>
    </ul>
    </div>
  </div>




</template>

<style scoped lang="scss">



.cards {
  margin-top: 50px;
  margin-bottom: 50px;
}

.card_items {
  display: flex;
  flex-wrap: wrap;
  gap: 29px;
  justify-content: center;
  @media (max-width: 1024px) {
      justify-content: center;
    }
  @media (max-width: 768px) {
    justify-content: center;
  }
}

.card-item{
  background-color: #fff;
  max-width: 370px;
  height: 254px;
  padding: 20px;
}

.card-content {
  width: 330px;
  overflow: hidden;
}

.card-image {
  display: flex;
  margin: 0 auto;
}

.team-member-name {
  text-align: center;
  margin-top: 20px;
  margin-bottom: 20px;
}


.team-member-who {
  text-align: center;
  line-height: 26px;
}

.team-member-mail {
  text-align: center;
  line-height: 26px;
  &:hover {
    cursor: pointer;
  }
}


.team-member-phone {
  text-align: center;
  line-height: 26px;
}

.team-member-name,
.team-member-who,
.team-member-mail,
.team-member-phone {
  overflow: hidden; /* Скрыть текст, который выходит за границы */
  white-space: nowrap; /* Предотвратить перенос текста на новую строку */
  text-overflow: ellipsis; /* Добавить многоточие в конце обрезанного текста */
}








@media (max-width: 2560px) {

  .card-item{
    max-width: 370px;
  }

  .card-content {
    width: 254px;
  }
}

@media (max-width: 1024px) {

  .card-item{
    max-width: 282px;
  }

  .card-content {
    width: 242px;
  }
}

@media (max-width: 768px) {
  .card-item{
    max-width: 344px;
  }

  .card-content {
    width: 304px;
  }
}

@media (max-width: 360px) {
  .card-item{
    max-width: 328px;
  }

  .card-content {
    width: 288px;
  }
}

</style>
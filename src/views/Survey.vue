<template>
  <div class="home container is-fluid">
    <div class="survey-head">
      <h1 class="title">Answer Survey</h1>
      <p>The Pride at Work Partner Inclusion Index Survey consists of <strong class="is-pride">35-40 questions</strong>, which are divided into <strong class="is-pride">eight themes</strong>.</p>
      <p>You may complete the theme sections in any order you choose. At any time, you can save your progress, and return later to continue.</p>
      <p>Depending on your responses to the survey questions, you may be prompted to provide supporting documentation. You can upload those documents on the survey page, or you can visit the "Documentation" page to see all required documents, and review your previously submitted documentation.</p>
      <div class="theme">
        <div class="theme-title-holder"><i class="fas fa-book"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy"> Anti-discrimination and Harassment Policies</router-link></h1></div>
        <div class="progress-holder">
          <div class="progress-indicator  complete"></div>
          <span>100%</span>
          <div class="progress-icon">
            <i class="fas fa-check checkmark"></i>
          </div>
          </div>
      </div>
      <div class="theme">
        <div class="theme-title-holder"><i class="fas fa-user"></i> <h1 class="theme-title"><router-link class="is-pride" to="/policy">Employee Resource Groups</router-link></h1></div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>
      <div class="theme">
        <div class="theme-title-holder"><i class="fas fa-handshake"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy"> Onboarding and Complaints Processes</router-link></h1>
        </div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>
      <div class="theme">
         <div class="theme-title-holder"><i class="fas fa-user-md"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy">Benefits Coverage</router-link></h1>
        </div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>
      <div class="theme">
         <div class="theme-title-holder"><i class="fas fa-clipboard"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy">Training Topics</router-link></h1>
         </div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>
      <div class="theme">
        <div class="theme-title-holder"><i class="fas fa-truck"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy"> Supplier Diversity</router-link></h1>
        </div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>
      <div class="theme">
         <div class="theme-title-holder"><i class="fas fa-child"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy"> Community Involvement</router-link></h1>
         </div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>
      <div class="theme">
          <div class="theme-title-holder"><i class="fas fa-comments"></i>
        <h1 class="theme-title"><router-link class="is-pride" to="/policy">Manager Support</router-link></h1>
          </div>
        <div class="progress-holder">
          <div class="progress-indicator"></div>
          <span>0%</span>
          <div class="progress-icon">
            <i class="far fa-circle"></i>
          </div>
          </div>
      </div>

    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'survey',

  methods: {
    showDefinition() {
      console.log(this);
    }
  }

}
</script>

<style scoped>
    section, .buttons {
        max-width: 600px;
        margin: 40px auto;
    }

  p {
    margin-bottom: 16px;
  }

    .survey-head {
      max-width: 700px;
      margin: 40px auto;
    }

    .sub-title {
      margin-bottom: 8px;
    }

    .is-pride {
      color: #92278f;
    }
    .link {
      color: #92278f;
    }
    .theme {
      padding: 0 32px;
    }

    .theme-title-holder {
      display: flex;
      align-items: center;
      margin-top: 24px;
      margin-left: -32px;
      color:#92278f;
    }
    .theme-title {
      font-size: 24px;
      font-weight: bold;
      margin-left: 16px;
    }
  .progress-holder {
    display: flex;
    width: 500px;
    justify-content: space-between;
    align-items: center;
  }
    .progress-indicator {
      height: 16px;
      width: 400px;
      border: 1px #92278f solid;
      border-radius: 2px;
    }

    .progress-indicator.complete {
      background-color: hsl(141, 71%, 48%);
    }

    .progress-icon .checkmark {
      color: hsl(141, 71%, 48%);
    }

</style>

<template>


  <div class="category">


    Over 20 years of Software Engineering experience in designing, analyzing, programming, maintaining, managing web based,
    distributed as well as client server Software Applications in multi-tier environment.
    <br />

    <strong>TECHNICAL SKILLS:</strong><br />

    Business Intelligence Tools: Power BI, Tableau 2018, SQL Server, Salesforce, SSRS, Crystal Report<br />

    ERP:	Infor SyteLIne<br />

    Languages:	C#, VB .NET<br />

    .NET Technologies:	ASP .NET MVC 5/4, ASP.NET CORE 2.1/2.0, ASP .NET Webform, Entity Framework CORE, ADO .NET, WPF,
    WCF, Winform, LINQ, Dapper <br />

    Other Web Technologies:	Single Page Architecture (SPA), HTML 5, HTML, CSS, Bootstrap, LESS, SASS, XML, JSon<br />

    Javascript Frameworks:	Vue.js, Angular JS, Angular, React, JQuery, AJAX, node.js,<br />

    SOA Technologies:	Restful Web API, WCF, Web Services, ASMX, Microservices, Enterprise Service Bus,
    Kubernetes, Postman, Swagger, Stackify, Fiddler<br />

    RDBMS:	SQL Server, Oracle, MySQL<br />

    Technical Architecture:	MVC, MVVM, MVP, Design patterns such as Repository, Factory, Singleton, Façade,
    Iterator, Observatory, UML, OOD, n-tier architecture <br />

    Source Control:	VSTS, SVN, Github, Bitbucket, TFS, Continuous Integration, Continuous Delivery, Docker,
    Test Driven Development (TDD) <br />

    Cloud Technologies:	Azure, Azure App Fabric, Amazon AWS <br />

    Integration/Unit Test:	XUnit, NUnit, MsBuild <br />

    <strong>Tools:	</strong>Visual Studio 2017, Telerik, extJS, Power BI, Tabelau 2018
    <br />

    SDLC:	Agile, Waterfall, Jira, Confluence, Scrum, WBS <br />

    <!--<nuxt-affix :list="list" category="guide" />-->
    <!--
  <div class="category__content Content Content--hasCarbon" :class="{'category__content--hidden': visible}">
    <nuxt-child/>
  </div>
  -->
    <div class="category__footer">
      <nuxt-footer />
    </div>
  </div>
</template>

<script>
import NuxtAffix from '~/components/Affix.vue'
import NuxtFooter from '~/components/Footer.vue'
export default {
  computed: {
    visible() { return this.$store.state.visibleAffix },
    list() { return this.$store.state.menu.guide }
  },
  components: {
    NuxtAffix,
    NuxtFooter
  }
}
</script>

<style>


</style>

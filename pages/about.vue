<template>


  <div class="category">
  
 
 Over 20 years of Software Engineering experience in designing, analyzing, programming, maintaining, managing web based, distributed as well as client server Software Applications in multi-tier environment.

TECHNICAL SKILLS:

Business Intelligence Tools: Power BI, Tableau 2018, SQL Server, Salesforce, SSRS, Crystal Report

ERP:	Infor SyteLIne

Languages:	C#, VB .NET

.NET Technologies:	ASP .NET MVC 5/4, ASP.NET CORE 2.1/2.0, ASP .NET Webform, Entity Framework CORE, ADO .NET, WPF, WCF, Winform, LINQ, Dapper

Other Web Technologies:	Single Page Architecture (SPA), HTML 5, HTML, CSS, Bootstrap, LESS, SASS, XML, JSon

Javascript Frameworks:	Vue.js, Angular JS, Angular, React, JQuery, AJAX, node.js,

SOA Technologies:	Restful Web API, WCF, Web Services, ASMX, Microservices, Enterprise Service Bus, Kubernetes, Postman, Swagger, Stackify, Fiddler

RDBMS:	SQL Server, Oracle, MySQL

Technical Architecture:	MVC, MVVM, MVP, Design patterns such as Repository, Factory, Singleton, Façade, Iterator, Observatory, UML, OOD, n-tier architecture

Source Control:	VSTS, SVN, Github, Bitbucket, TFS, Continuous Integration, Continuous Delivery, Docker, Test Driven Development (TDD)

Cloud Technologies:	Azure, Azure App Fabric, Amazon AWS

Integration/Unit Test:	XUnit, NUnit, MsBuild

Tools:	Visual Studio 2017, Telerik, extJS, Power BI, Tabelau 2018

SDLC:	Agile, Waterfall, Jira, Confluence, Scrum, WBS 
  
    <!--<nuxt-affix :list="list" category="guide" />-->
    
    <!--
    <div class="category__content Content Content--hasCarbon" :class="{'category__content--hidden': visible}">
      <nuxt-child/>
    </div>
    -->
    <div class="category__footer">
      <nuxt-footer/>
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

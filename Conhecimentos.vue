<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/qualificacoes.jpg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <p> 
        <span class="subheading font-weight-bold">
          Felipe Vieira de Souza
        </span><br>
        <span class="subheading font-weight-regular">
          Conhecimento, Experiência e Qualificações
        </span>
        </p>

        
 
      </v-col>
    </v-row>

<v-content>
  <v-flex fill-height>
  <table border=1 id="tabla">
    <thead>
      <tr>
        <td rowspan=2 colspan=2 class="assunto">Assunto</td>
        <td colspan=5>Nível de conhecimento</td>
        <td colspan=4>Nível de utilização</td>
        <td rowspan=2><span class=depe>Utiliza/aplica Atualmente</span></td>
        <td rowspan=2><span class=depe>Pode Ensinar</span></td>
      </tr>
      <tr style="height:180px">
        <td><span class="depe inferior">não conheço</span></td>
        <td><span class="depe">já ouvi falar</span></td>
        <td><span class="depe">conheço pouco</span></td>
        <td><span class="depe">conheço o necessário</span></td>
        <td><span class="depe">conheço muito</span></td>
        <td><span class="depe">nenhuma</span></td>
        <td><span class="depe">baixa</span></td>
        <td><span class="depe">média</span></td>
        <td><span class="depe">alta</span></td>
      </tr>

    </thead>
    <tbody>
      <tr>
        <td rowspan=3><span class="depe">banco de dados</span></td>
          <td>MongoDB</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td>X</td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
         <td>PostGres SQL</td>
          <td>X</td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td>X</td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td></td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>Microsoft SQL Server</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td>X</td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>

      <tr>
          <td rowspan=6><span class="depe">Linguagem SQL</span></td>
          <td>Select</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td>X</td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
          <td>Insert/Update/Delete</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td>X</td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>View</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td>X</td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td></td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
          <td>Function</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td>X</td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td></td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>Trigger</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td>X</td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td></td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>PK, FK, Sequence, Index<br>
        e Unique</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td>X</td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td></td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td rowspan=7><span class="depe">Linguagens de Programação</span></td>
       <td>Node.js</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td>X</td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
         <td>CSS</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td>X</td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>JavaScript</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td>X</td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>Visual Basic</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td>X</td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>Vue.js</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td>X</td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td>X</td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>PHP</td>
          <td>X</td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td></td> <!-- conheço muito -->
          <td>X</td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td></td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td></td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td>asp.NET</td>
          <td></td> <!--não conheço -->
          <td></td> <!-- já ouvi falar -->
          <td></td> <!-- conheço pouco -->
          <td></td> <!-- conheço o necessário -->
          <td>X</td> <!-- conheço muito -->
          <td></td> <!-- nenhuma -->
          <td></td> <!-- Baixa -->
          <td>X</td> <!-- Media -->
          <td></td> <!-- Alta -->
          <td>X</td> <!-- aplico atualmente -->
          <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td colspan=2>Desenvolvimento de Sistemas</td>
        <td></td> <!--não conheço -->
        <td></td> <!-- já ouvi falar -->
        <td></td> <!-- conheço pouco -->
        <td>X</td> <!-- conheço o necessário -->
        <td></td> <!-- conheço muito -->
        <td></td> <!-- nenhuma -->
        <td></td> <!-- Baixa -->
        <td>X</td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td>X</td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>
      
            <tr>
        <td colspan=2>Documentação de Sistemas</td>
        <td></td> <!--não conheço -->
        <td></td> <!-- já ouvi falar -->
        <td>X</td> <!-- conheço pouco -->
        <td></td> <!-- conheço o necessário -->
        <td></td> <!-- conheço muito -->
        <td></td> <!-- nenhuma -->
        <td>X</td> <!-- Baixa -->
        <td></td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td></td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>
      
      <tr>
        <td colspan=2>BI - Business Intelligence</td>
        <td></td> <!--não conheço -->
        <td>X</td> <!-- já ouvi falar -->
        <td></td> <!-- conheço pouco -->
        <td></td> <!-- conheço o necessário -->
        <td></td> <!-- conheço muito -->
        <td>X</td> <!-- nenhuma -->
        <td></td> <!-- Baixa -->
        <td></td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td></td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>

            <tr>
        <td colspan=2>PENTAHO</td>
        <td></td> <!--não conheço -->
        <td>x</td> <!-- já ouvi falar -->
        <td></td> <!-- conheço pouco -->
        <td></td> <!-- conheço o necessário -->
        <td></td> <!-- conheço muito -->
        <td>x</td> <!-- nenhuma -->
        <td></td> <!-- Baixa -->
        <td></td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td></td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>

      <tr>
        <td colspan=2>Gerador de Relatórios</td>
        <td>X</td> <!--não conheço -->
        <td></td> <!-- já ouvi falar -->
        <td></td> <!-- conheço pouco -->
        <td></td> <!-- conheço o necessário -->
        <td></td> <!-- conheço muito -->
        <td>X</td> <!-- nenhuma -->
        <td></td> <!-- Baixa -->
        <td></td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td></td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>
      <tr>
        <td colspan=2>Excel</td>
        <td></td> <!--não conheço -->
        <td></td> <!-- já ouvi falar -->
        <td></td> <!-- conheço pouco -->
        <td></td> <!-- conheço o necessário -->
        <td>X</td> <!-- conheço muito -->
        <td></td> <!-- nenhuma -->
        <td></td> <!-- Baixa -->
        <td>X</td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td></td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>
            <tr>
        <td colspan=2>Angularjs 1.5 e 1.6</td>
        <td></td> <!--não conheço -->
        <td></td> <!-- já ouvi falar -->
        <td></td> <!-- conheço pouco -->
        <td>X</td> <!-- conheço o necessário -->
        <td></td> <!-- conheço muito -->
        <td></td> <!-- nenhuma -->
        <td></td> <!-- Baixa -->
        <td>X</td> <!-- Media -->
        <td></td> <!-- Alta -->
        <td>X</td> <!-- aplico atualmente -->
        <td></td> <!-- posso ensinar -->
      </tr>

    </tbody>
  </table>
  </v-flex>
</v-content>

  </v-container>


</template>

<script>
  export default {
    name: 'Qualificacoes',

    data: () => ({
     
    }),  
    components: {
     
    }
    
  }
</script>
<style lang = "scss"> 

@import "../../node_modules/ag-grid-community/dist/styles/ag-grid.css";
@import "../../node_modules/ag-grid-community/dist/styles/ag-theme-balham.css";

.assunto{
  width:140px;
  vertical-align: bottom;
padding: 10px;
}

#span{
  padding: 10px;
}
#td{
  padding: 10px;
}

#tabla thead {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: rgb(28, 115, 165);
  color: white;
}
.inferior{
  vertical-align:bottom;
  padding: 10px;
}

.depe{
  writing-mode: vertical-lr;
  text-align: left;
  padding: 10px;
}





table {
    border-collapse:collapse;
    width:100%;
    max-width:700px;
    min-width:400px;
    text-align:center;
}

caption {
    caption-side:bottom;
    font-weight:bold;
    font-style:italic;
    margin:4px;
}

</style>
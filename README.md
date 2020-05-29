# Concatena-o
Exercício de Concatenação com Denilson Bonatti
<?xml version="1.0"?>
<flowgorithm fileversion="2.11">
    <attributes>
        <attribute name="name" value=""/>
        <attribute name="authors" value="mario"/>
        <attribute name="about" value=""/>
        <attribute name="saved" value="2020-05-29 05:22:41 "/>
        <attribute name="created" value="bWFyaW87TEFQVE9QLUwzS0RERkFDOzIwMjAtMDUtMjc7IjAzOjE0OjU3ICI7Mjc3OA=="/>
        <attribute name="edited" value="bWFyaW87TEFQVE9QLUwzS0RERkFDOzIwMjAtMDUtMjk7IjA1OjIyOjQxICI7NTsyODg2"/>
    </attributes>
    <function name="Main" type="None" variable="">
        <parameters/>
        <body>
            <declare name="Nome, Sobrenome" type="String" array="False" size=""/>
            <output expression="&quot;Digite seu nome:&quot;" newline="True"/>
            <input variable="Nome"/>
            <output expression="&quot;Digite seu Sobrenome:&quot;" newline="True"/>
            <input variable="Sobrenome"/>
            <output expression="&quot;O Seu Nome &#233;:&quot; &amp; Nome &amp; &quot; e seu Sobrenome &#233;:&quot; &amp; Sobrenome" newline="True"/>
            <declare name="nota1, nota2, nota3, nota4, soma, media" type="Real" array="False" size=""/>
            <output expression="&quot;Digite a Primeira Nota:&quot;" newline="True"/>
            <input variable="nota1"/>
            <output expression="&quot;Digite a Segunda Nota:&quot;" newline="True"/>
            <input variable="nota2"/>
            <output expression="&quot;Digite a Terceira Nota:&quot;" newline="True"/>
            <input variable="nota3"/>
            <output expression="&quot;Digite a Quarta Nota:&quot;" newline="True"/>
            <input variable="nota4"/>
            <assign variable="soma" expression="(nota1+nota2+nota3+nota4)"/>
            <assign variable="media" expression="(nota1+nota2+nota3+nota4)/4"/>
            <output expression="&quot;A Soma das suas Notas &#233;:&quot; &amp; soma &amp; &quot; Sua M&#233;dia Final &#233;:&quot; &amp; media" newline="True"/>
        </body>
    </function>
</flowgorithm>

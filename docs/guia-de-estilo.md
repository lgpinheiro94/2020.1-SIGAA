# Guia de Estilo

## 1. Introdução

### 1.1. Objetivo do guia de estilo

### 1.2. Organização e conteúdo do guia de estilo

### 1.3. Público alvo do guia de estilos

### 1.4. Como utilizar o guia

### 1.5. Como manter o guia

## 2. Resultado de análise

### 2.1. Descrição do ambiente de trabalho do usuário

## 3. Elementos de interface

## 3.1. Tipografia

<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');
</style>

A fonte utilizada é a Open Sans.

Open Sans Regular é a fonte padrão.

Open Sans Semibold deve ser usada em textos com algum destaque, como labels de formulários.

Open Sans Bold deve ser usada em textos com maior destaque, como títulos.


### 3.1.1. Open Sans Regular

<div style="font-family: 'Open Sans', sans-serif;">
    <p style="font-weight: 400; font-size: 14px;">Open Sans Regular 14</p>
    <p style="font-weight: 400; font-size: 16px;">Open Sans Regular 16</p>
    <p style="font-weight: 400; font-size: 18px;">Open Sans Regular 18</p>
    <p style="font-weight: 400; font-size: 20px;">Open Sans Regular 20</p>
    <p style="font-weight: 400; font-size: 22px;">Open Sans Regular 22</p>
</div>

### 3.1.2. Open Sans Semibold

<div style="font-family: 'Open Sans', sans-serif;">
    <p style="font-weight: 600; font-size: 14px;">Open Sans Semibold 14</p>
    <p style="font-weight: 600; font-size: 16px;">Open Sans Semibold 16</p>
    <p style="font-weight: 600; font-size: 18px;">Open Sans Semibold 18</p>
    <p style="font-weight: 600; font-size: 20px;">Open Sans Semibold 20</p>
    <p style="font-weight: 600; font-size: 22px;">Open Sans Semibold 22</p>
</div>

### 3.1.3. Open Sans Bold

<div>
    <p style="font-weight: 700; font-size: 14px;">Open Sans Bold 14</p>
    <p style="font-weight: 700; font-size: 16px;">Open Sans Bold 16</p>
    <p style="font-weight: 700; font-size: 18px;">Open Sans Bold 18</p>
    <p style="font-weight: 700; font-size: 20px;">Open Sans Bold 20</p>
    <p style="font-weight: 700; font-size: 22px;">Open Sans Bold 22</p>
</div>

## 3.2. Símbolos não tipográficos

## 3.3. Cores

Foram escolhidas as cores da logo da UnB, e algumas cores apresentadas na página de login do próprio SIGAA.

<style>
    .color {
        width: 5em;
        height: 5em;
        float:left;
    }
    .legenda {
        width: 5em;
        float:left;
        text-align: center;
    }
</style>

<div class="color" style="background-color: #000000"></div>
<div class="color" style="background-color: #00659E"></div>
<div class="color" style="background-color: #0B4373"></div>
<div class="color" style="background-color: #3C8134"></div>
<div class="color" style="background-color: #D0DAE0"></div>
<div class="color" style="background-color: #DAE4EB"></div>
<div class="color" style="background-color: #F0F4F5"></div>
<div class="color" style="background-color: #FFFFFF"></div>

<p class="legenda">#000000</p>
<p class="legenda">#00659E</p>
<p class="legenda">#0B4373</p>
<p class="legenda">#3C8134</p>
<p class="legenda">#D0DAE0</p>
<p class="legenda">#DAE4EB</p>
<p class="legenda">#F0F4F5</p>
<p style="width: 5em; text-align: center;">#FFFFFF</p>

## 3.4. Links

normal: <p style="color: #01376f;">Link</p>
hover: <p style="color: #53a825">Link</p>
visited: <p style="color: #005500">Link</p>

## 3.5. Formulário

<table style="background-color: #ddd">
    <colgroup>
        <col span="1" style="width: auto;">
        <col span="1" style="width: 40%">
    </colgroup>
    <tr>
        <td><input type="checkbox"></td>
        <td><label>ITEM NAME</label></td>
        <td><input type="text"></td>
    </tr>
    <tr>
        <td><input type="checkbox"></td>
        <td><label>ITEM NAME</label></td>
        <td>
            <select>
                <option value="opção 1">Opção 1</option>
                <option value="opção 2">Opção 2</option>
            </select>
        </td>
    </tr>
</table>

## 3.6. Botão

<style>
    #btn {
        background-color: #00659E;
        font-weight: 600;
        color: #fff;
        border-radius: 9px;
        padding: 0.5em 1em;
        border: none;
    }
</style>
<div>
    <button id="btn">BOTÃO</button>
</div>

## 3.7. Listagem

<style>
    #tab {
        width: 100%;
    }
    #tab tr{
        height: 2.5em;
    }
    #sh {
        background-color: #00659E;
    }
    .par {
        background-color: #F0F4F5;
    }
    .impar {
        background-color: #DAE4EB;
    }
</style>

<table id="tab">
    <th id="sh"><td></td></th>
    <tr class="par"><td></td></tr>
    <tr class="impar"><td></td></tr>
    <tr class="par"><td></td></tr>
    <tr class="impar"><td></td></tr>
</table>

## 3.8. Menu

<style>
    #ulist {
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #DAE4EB;
    }
    #list {
        float: left;
    }
    #list a, .dropbtn {
        display: inline-block;
        color: white;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }
    #list a:hover, .dropdown:hover, .dropbtn {
        background-color: #00659E;
    }
    #list.dropdown {
        display: inline-block;
    }
    .drop-content {
        display: none;
        position: absolute;
        background-color: #00659E;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
        z-index: 1;
    }
    .drop-content a {
        color: white;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
        text-align: left;
    }
    .drop-content a:hover {
        background-color: #3C8134;
    }
    .dropdown:hover .drop-content {
        display: block;
    }
</style>

<ul id="ulist">
    <li class="dropdown" id="list">
        <a href="#" class="dropbtn">Menu</a>
        <div class="drop-content">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>
    </li>
</ul>
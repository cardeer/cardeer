<div id="title">
    <h2>Hello</h2>
    <h2>I</h2>
    <h2>Am</h2>
    <h2 id="cardeer">CARDEER</h2>
</div>

<h4 id="sub-title">I'm a web developer, studying Computer Science at King Mongkut's Institute of Technology Ladkrabang</h4>

<div class="slider">
<span>I WANT SOME COFFEE !!</span>
</div>

<h3 style="text-align: center;">Love Japanese Songs</h4>
<table class="table">
<thead>
<tr>
    <th width="50">#</th>
    <th>Name</th>
</tr>
</thead>

<tbody>
    <tr>
        <td>1</td>
        <td>Minami</td>
    </tr>
    <tr>
        <td>2</td>
        <td>ClariS</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Asaka</td>
    </tr>
    <tr>
        <td>4</td>
        <td>Aimer</td>
    </tr>
</tbody>
</table>

<style>
#title{
    display: flex;
    margin-top: 20px;
    justify-content: center;
}

#title > :nth-child(2n){
    display: inline-block;
    font-weight: bold;
    letter-spacing:5px;
    transform-origin: center;
    transform: rotateZ(10deg);
}

#title > :nth-child(2n + 1){
    display: inline-block;
    font-weight: bold;
    letter-spacing:5px;
    transform-origin: center;
    transform: rotateZ(-10deg);
}

#title > :not(:last-child){
    margin-right: 20px;
}

#cardeer{
    color: #EA3D3D;
}

#sub-title{
    margin-top: 20px;
}

.table{
    width: 100%;
    margin: 10px 0;
}

.table tr > td:nth-child(2), th:nth-child(2){
    text-align: center;
}

.slider{
    position: relative;
    margin: 10px 0;
    height: 20px;
}

.slider > span{
    position: absolute;
    width: 170px;
    /* background-color: red; */
    font-weight: bold;
    animation: slider 10s linear infinite;
}

@keyframes slider{
    0%, 100% {
        left: 0%;
    }

    50%{
        left: calc(100% - 170px);
    }
}
</style>

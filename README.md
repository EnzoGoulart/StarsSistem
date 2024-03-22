# Sistema de avaliação com até 5 estrelas que aceita numeros decimais 

//Props:
//rate: numero da nota em ingles ex 4.5 OBRIGATÓRIO
//width: width e height DEFAULT "18px"
//marginRight: Distância da string da nota DEFAULT "0"

## Atenção - Definir as cores corretamente / alterar para as suas
:root{ 
    --Text: #101010; 
    --Yellow: #b7b91a;
}

## Exemplo de uso

<div className="starsSellerPRO">
    <Stars rate="3.5" width="16px" marginRight="5px"/>
    <p>3,5</p>
</div>

.starsSellerPRO {
    display: flex;
    position: relative;
    left: -10px;
    font-weight: bold;
    margin-left: 10px;
} 

## Como alterar o formato das estrelas? 

Altere o clip-path do .faStar em **https://bennettfeely.com/clippy/** ou faça o seu próprio.

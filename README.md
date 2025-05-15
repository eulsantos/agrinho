<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mudanças Climáticas: Entenda e Aja</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Entenda e Aja Contra as Mudanças Climáticas</h1>
    </header>

    <nav>
        <a href="#introducao">Introdução</a>
        <a href="#causas">Causas</a>
        <a href="#consequencias">Consequências</a>
        <a href="#solucoes">Soluções</a>
        <a href="#dados">Dados e Visualizações</a>
        <a href="#acao">Aja Agora</a>
    </nav>

    <div class="container">
        <section id="introducao">
            <h2>O Que São as Mudanças Climáticas?</h2>
            <p>As mudanças climáticas referem-se a alterações de longo prazo nas temperaturas e nos padrões climáticos. Essas mudanças podem ser naturais, como por meio de variações no ciclo solar. No entanto, desde o século XIX, as atividades humanas têm sido o principal motor das mudanças climáticas, principalmente devido à queima de combustíveis fósseis (como carvão, petróleo e gás) que liberam gases de efeito estufa na atmosfera.</p>
        </section>

        <section id="causas">
            <h2>Principais Causas</h2>
            <ul>
                <li><strong>Queima de Combustíveis Fósseis:</strong> Liberação de dióxido de carbono (CO2) e outros gases de efeito estufa.</li>
                <li><strong>Desmatamento:</strong> Redução da capacidade da Terra de absorver CO2.</li>
                <li><strong>Agricultura Intensiva:</strong> Emissão de metano (CH4) e óxido nitroso (N2O).</li>
                <li><strong>Processos Industriais:</strong> Liberação de diversos gases de efeito estufa.</li>
                <li><strong>Aumento da População e Consumo:</strong> Maior demanda por recursos e energia.</li>
            </ul>
        </section>

        <section id="consequencias">
            <h2>Consequências das Mudanças Climáticas</h2>
            <ul>
                <li><strong>Aumento da Temperatura Global:</strong> Ondas de calor mais frequentes e intensas.</li>
                <li><strong>Elevação do Nível do Mar:</strong> Inundações costeiras e erosão.</li>
                <li><strong>Eventos Climáticos Extremos:</strong> Secas, tempestades, furacões e incêndios florestais mais severos.</li>
                <li><strong>Acidificação dos Oceanos:</strong> Impacto na vida marinha e nos ecossistemas.</li>
                <li><strong>Perda de Biodiversidade:</strong> Extinção de espécies e desequilíbrio ecológico.</li>
                <li><strong>Impactos na Saúde Humana:</strong> Doenças relacionadas ao calor, problemas respiratórios e insegurança alimentar.</li>
            </ul>
        </section>

        <section id="solucoes">
            <h2>Possíveis Soluções</h2>
            <ul>
                <li><strong>Transição para Energias Renováveis:</strong> Solar, eólica, hidrelétrica, geotérmica.</li>
                <li><strong>Eficiência Energética:</strong> Reduzir o consumo de energia em todos os setores.</li>
                <li><strong>Reflorestamento e Conservação de Florestas:</strong> Aumentar a absorção de CO2.</li>
                <li><strong>Agricultura Sustentável:</strong> Práticas que reduzem as emissões de gases de efeito estufa.</li>
                <li><strong>Transporte Sustentável:</strong> Veículos elétricos, transporte público eficiente, ciclovias.</li>
                <li><strong>Economia Circular:</strong> Reduzir, reutilizar e reciclar materiais.</li>
                <li><strong>Políticas Públicas:</strong> Acordos internacionais, regulamentações e incentivos para a redução de emissões.</li>
                <li><strong>Conscientização e Educação:</strong> Informar e engajar a população sobre a importância da ação climática.</li>
            </ul>
        </section>

        <section id="dados">
            <h2>Dados e Visualizações</h2>
            <p>Visualizações de dados podem ajudar a entender a magnitude das mudanças climáticas.</p>
            <div class="data-visualization">
                <h3>Gráfico de Temperatura Global (Exemplo)</h3>
                <canvas id="temperature-chart"></canvas>
            </div>
            <div class="data-visualization">
                <h3>Gráfico de Concentração de CO2 na Atmosfera (Exemplo)</h3>
                <canvas id="co2-chart"></canvas>
            </div>
            <p><strong>Nota:</strong> Estes gráficos são exemplos e seriam preenchidos com dados reais usando JavaScript e bibliotecas de gráficos como Chart.js.</p>
        </section>

        <section id="acao" class="call-to-action">
            <h3>Aja Agora! Faça a Diferença.</h3>
            <p>Cada ação conta na luta contra as mudanças climáticas. Informe-se, adote práticas sustentáveis e pressione por mudanças em sua comunidade e no mundo.</p>
            <button id="acao-button">Saiba Como Contribuir</button>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Conscientização sobre Mudanças Climáticas</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="script.js"></script>
</body>
</html>
/* style.css */

body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #22577E;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    background-color: #5584AC;
    color: white;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
}

.container {
    max-width: 960px;
    margin: 20px auto;
    padding: 20px;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section {
    margin-bottom: 30px;
}

h2 {
    color: #22577E;
}

.data-visualization {
    margin-top: 20px;
    border: 1px solid #ccc;
    padding: 15px;
    border-radius: 5px;
    background-color: #f9f9f9;
}

#temperature-chart, #co2-chart {
    width: 100%;
    height: 300px;
}

.call-to-action {
    background-color: #80ED99;
    padding: 20px;
    border-radius: 5px;
    text-align: center;
}

.call-to-action h3 {
    color: #386641;
}

.call-to-action button {
    background-color: #386641;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}
// script.js

// Exemplo de dados para o gráfico de temperatura (substituir por dados reais)
const temperatureData = {
    labels: ['1900', '1920', '1940', '1960', '1980', '2000', '2020'],
    datasets: [{
        label: 'Variação da Temperatura Global (°C)',
        data: [-0.2, -0.1, 0.05, 0.15, 0.3, 0.6, 1.0],
        borderColor: '#FF6B6B',
        fill: false
    }]
};

const temperatureChart = new Chart(
    document.getElementById('temperature-chart'),
    {
        type: 'line',
        data: temperatureData,
        options: {
            responsive: true,
            scales: {
                y: {
                    title: {
                        display: true,
                        text: 'Variação de Temperatura (°C)'
                    }
                },
                x: {
                    title: {
                        display: true,
                        text: 'Ano'
                    }
                }
            }
        }
    }
);

// Exemplo de dados para o gráfico de CO2 (substituir por dados reais)
const co2Data = {
    labels: ['1950', '1970', '1990', '2010', '2023'],
    datasets: [{
        label: 'Concentração de CO2 (ppm)',
        data: [310, 330, 355, 390, 417],
        borderColor: '#5584AC',
        fill: false
    }]
};

const co2Chart = new Chart(
    document.getElementById('co2-chart'),
    {
        type: 'line',
        data: co2Data,
        options: {
            responsive: true,
            scales: {
                y: {
                    title: {
                        display: true,
                        text: 'Concentração de CO2 (partes por milhão)'
                    }
                },
                x: {
                    title: {
                        display: true,
                        text: 'Ano'
                    }
                }
            }
        }
    }
);

// Evento de clique para o botão "Saiba Como Contribuir"
document.getElementById('acao-button').addEventListener('click', function() {
    alert('Você clicou para agir! Informe-se sobre como pode contribuir.');
});

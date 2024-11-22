<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Sistema de Gerenciamento de Oficina Mecânica</h1>
    <h2>Descrição do Projeto Conceitual</h2>
    <p>Este projeto apresenta um esquema conceitual para um sistema de gerenciamento de uma oficina mecânica. O sistema foi projetado para controlar e gerenciar a execução de ordens de serviço, facilitando o processo desde a entrada do veículo até a conclusão do serviço.</p>
    <h2>Contexto</h2>
    <p>Uma oficina mecânica necessita de um sistema para gerenciar suas operações diárias. Os clientes trazem seus veículos para reparos ou revisões periódicas, e o sistema deve ser capaz de acompanhar todo o processo, desde a recepção do veículo até a entrega ao cliente.</p>
    <h2>Principais Entidades</h2>
    <ul>
        <li><strong>Cliente:</strong> Armazena informações dos clientes da oficina.</li>
        <li><strong>Veículo:</strong> Registra os dados dos veículos atendidos.</li>
        <li><strong>Mecânico:</strong> Contém informações sobre os mecânicos da oficina.</li>
        <li><strong>Equipe:</strong> Agrupamento de mecânicos para realizar serviços.</li>
        <li><strong>Ordem de Serviço (OS):</strong> Documento central que registra todo o processo de atendimento.</li>
        <li><strong>Serviço:</strong> Catálogo de serviços oferecidos pela oficina.</li>
        <li><strong>Peça:</strong> Inventário de peças disponíveis para uso nos reparos.</li>
    </ul>
    <h2>Funcionalidades Principais</h2>
    <ol>
        <li>Registro e gerenciamento de clientes e seus veículos.</li>
        <li>Criação e acompanhamento de ordens de serviço.</li>
        <li>Alocação de equipes de mecânicos para cada OS.</li>
        <li>Cálculo automático do valor do serviço baseado em mão-de-obra e peças utilizadas.</li>
        <li>Controle de estoque de peças.</li>
        <li>Acompanhamento do status de cada ordem de serviço.</li>
        <li>Registro de aprovações de serviço pelo cliente.</li>
    </ol>
    <h2>Relacionamentos Chave</h2>
    <ul>
        <li>Um cliente pode ter múltiplos veículos.</li>
        <li>Cada OS está associada a um veículo e um cliente.</li>
        <li>Uma equipe pode trabalhar em várias OS, e uma OS é atendida por uma equipe.</li>
        <li>Cada OS pode incluir múltiplos serviços e peças.</li>
    </ul>
    <h2>Considerações de Design</h2>
    <p>O esquema foi projetado para garantir a integridade dos dados e facilitar consultas comuns, como histórico de serviços por veículo, produtividade das equipes, e análise de custos e receitas. Índices foram adicionados para otimizar o desempenho das consultas mais frequentes.</p>
    <h2>Conclusão</h2>
    <p>Este esquema conceitual fornece uma base sólida para o desenvolvimento de um sistema completo de gerenciamento de oficina mecânica, capaz de atender às necessidades de controle operacional e administrativo do negócio.</p>
</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projet RNCP – Pilotage IndusFab</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #2980b9;
            --bg-light: #f4f7f6;
            --text-color: #333;
            --border-color: #dcdde1;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-light);
            margin: 0;
            padding: 0;
        }

        header {
            background-color: var(--primary-color);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
        }

        .container {
            max-width: 1000px;
            margin: -40px auto 40px auto;
            background: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        h1 { margin: 0; font-size: 2.2rem; text-transform: uppercase; letter-spacing: 1px; }
        h2 { color: var(--primary-color); border-bottom: 2px solid var(--accent-color); padding-bottom: 10px; margin-top: 40px; }
        h3 { color: var(--secondary-color); margin-top: 25px; }

        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; }
        .card { padding: 20px; border: 1px solid var(--border-color); border-radius: 4px; background: #fafafa; }

        .cta-button {
            display: inline-block;
            background: var(--accent-color);
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            margin-top: 20px;
            transition: background 0.3s;
        }

        .cta-button:hover { background: #1f6391; }

        table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        th, td { text-align: left; padding: 12px; border-bottom: 1px solid var(--border-color); }
        th { background-color: #f8f9fa; color: var(--primary-color); }

        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }

        .footer { text-align: center; font-size: 0.9rem; color: #7f8c8d; margin-top: 50px; padding-bottom: 20px; }
    </style>
</head>
<body>

<header>
    <h1>Pilotage de Projet : IndusFab</h1>
    <p>Cadre RNCP - Mise en œuvre de solutions de gestion industrielle</p>
</header>

<div class="container">
    
    <section>
        <h2>1. Contexte de l'Entreprise</h2>
        <p><strong>IndusFab</strong> opère dans la fabrication de composants de haute précision pour les industries aéronautiques et automobiles. Avec un effectif de 250 salariés et un chiffre d'affaires de 40 M€, l'entreprise doit répondre à des exigences réglementaires et de qualité strictes (ISO, RGPD, NIS2).</p>
        
        <div class="grid">
            <div class="card">
                <h3>Implantation et Infrastructure</h3>
                <ul>
                    <li>Siège social : Direction, R&D, IT centralisée.</li>
                    <li>Site industriel : Lignes automatisées et environnements OT.</li>
                    <li>Écosystème Cloud : Microsoft 365 & Azure.</li>
                </ul>
            </div>
            <div class="card">
                <h3>Parties Prenantes</h3>
                <ul>
                    <li>Clients : Donneurs d'ordres aéronautiques.</li>
                    <li>Externes : Infogérance IT, fournisseurs de matières.</li>
                    <li>Régulateurs : Autorités de certification.</li>
                </ul>
            </div>
        </div>
    </section>

    <section>
        <h2>2. Dispositifs de Pilotage</h2>
        <p>La gestion du projet repose sur une dualité d'outils permettant de concilier vision stratégique et agilité opérationnelle.</p>
        <center>
            <a href="https://gin-gitaxias.github.io/RNCP-Project/Gantt%26Kanban.html" class="cta-button">Accéder aux Tableaux de Bord (Gantt & Kanban)</a>
        </center>
    </section>

    <section>
        <h2>3. Méthodologie de Gestion de Projet</h2>
        <p>L'organisation a retenu la méthodologie <strong>Scrum</strong>, adaptée au cycle de vie industriel :</p>
        <ul>
            <li><strong>Itérations :</strong> Sprints de 2 à 3 semaines pour assurer des livrables réguliers.</li>
            <li><strong>Gouvernance :</strong> Collaboration directe entre le Product Owner (Métier) et l'équipe technique pluridisciplinaire.</li>
            <li><strong>Outils :</strong> Flux Kanban pour la gestion du "Work in Progress" (WIP) et Daily Management.</li>
        </ul>
    </section>

    <section>
        <h2>4. Indicateurs de Performance (KPI)</h2>
        <table>
            <thead>
                <tr>
                    <th>Catégorie</th>
                    <th>Indicateur</th>
                    <th>Objectif</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Planning</td>
                    <td>Respect des jalons clés</td>
                    <td>Écart prévu vs réel < 5%</td>
                </tr>
                <tr>
                    <td>Productivité</td>
                    <td>Vélocité de l'équipe</td>
                    <td>Nombre de points/tâches par sprint</td>
                </tr>
                <tr>
                    <td>Qualité</td>
                    <td>Taux de non-conformité</td>
                    <td>Réduction des retours en revue</td>
                </tr>
                <tr>
                    <td>Opérationnel</td>
                    <td>Lead Time</td>
                    <td>Optimisation du cycle de livraison</td>
                </tr>
            </tbody>
        </table>
    </section>

    <div class="footer">
        Projet RNCP - IndusFab - Document de Synthèse - 2024
    </div>
</div>

</body>
</html>

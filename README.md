<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maintenance Digitalisée - Voie 01</title>
    <style>
        /* Utilisation de vos codes couleurs */
        :root {
            --bleu-principal: #1C2F50;
            --bleu-fonce: #14294C;
            --bleu-clair: #1A3050;
            --blanc: #FFFFFF;
            --gris-clair: #AAB2BB;
        }

        body { 
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; 
            background-color: var(--bleu-principal); /* Fond bleu foncé principal */
            color: var(--blanc);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 10px;
        }

        .container { 
            max-width: 450px; 
            width: 100%;
            background: var(--blanc); /* Carte blanche pour le contraste */
            border-radius: 20px; 
            padding: 30px; 
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
            color: #333; /* Texte sombre sur fond blanc */
        }
        
        .logo-box {
            text-align: center;
            margin-bottom: 25px;
        }

        .logo { 
            max-width: 180px; 
            height: auto; 
        }
        
        h1 { 
            color: var(--bleu-principal); 
            font-size: 1.5rem; 
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .subtitle { 
            color: var(--gris-clair); 
            font-size: 0.9rem; 
            font-weight: bold;
            margin-bottom: 30px;
            display: block;
        }
        
        /* Boutons avec vos variantes de bleu */
        .btn { 
            display: flex; 
            align-items: center; 
            justify-content: center;
            width: 100%; 
            padding: 16px 0; 
            margin: 15px 0;
            background-color: var(--bleu-principal); 
            color: var(--blanc); 
            text-decoration: none;
            border-radius: 12px; 
            font-weight: bold; 
            font-size: 1.1rem;
            transition: all 0.3s ease;
            border: none;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .btn:hover { 
            background-color: var(--bleu-fonce); 
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.2);
        }

        .btn-icon { 
            margin-right: 15px; 
            font-size: 1.3rem; 
        }

        /* Footer avec votre nom */
        .footer { 
            margin-top: 40px; 
            font-size: 0.8rem; 
            color: var(--gris-clair); 
            border-top: 1px solid #eee; 
            padding-top: 20px;
            line-height: 1.5;
        }

        .creator { 
            font-weight: bold; 
            color: var(--bleu-clair);
            font-size: 0.9rem;
        }

        /* Indicateur de statut technique */
        .status-bar {
            background: #eef2f7;
            padding: 8px;
            border-radius: 50px;
            font-size: 0.75rem;
            margin-bottom: 20px;
            color: var(--bleu-principal);
            display: inline-block;
            padding: 5px 15px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- LOGO -->
        <div class="logo-box">
            <img src="logo_entreprise.png" alt="Logo Entreprise" class="logo">
        </div>

        <div style="text-align: center;">
            <div class="status-bar">● VOIE AFFECTÉE</div>
            <h1>ARMOIRE ÉLECTRIQUE</h1>
            <span class="subtitle">PÉAGE MED V : GARE 331 - VOIE 01</span>
        </div>
        
        <!-- LIENS VERS VOS FICHIERS PDF -->
        <a href="schema_electrique.pdf" target="_blank" class="btn">
            <span class="btn-icon">📋</span> SCHÉMA ÉLECTRIQUE
        </a>
        
        <a href="details_equipements.pdf" target="_blank" class="btn">
            <span class="btn-icon">⚙️</span> DÉTAILS ÉQUIPEMENTS
        </a>
        
        <a href="securite_consignation.pdf" target="_blank" class="btn">
            <span class="btn-icon">🔐</span> SÉCURITÉ / CONSIGNATION
        </a>

        <!-- VOTRE SIGNATURE -->
        <div class="footer">
            <p>Module de Maintenance Digitale v1.0<br>
            Ce domaine a été créé par <br>
            <span class="creator">Mr Abdelali Adriouch</span></p>
        </div>
    </div>

</body>
</html>

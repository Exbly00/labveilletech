---
title: "Création de flux de travail basés sur l'IA et optimisés par MCP"
date: 2026-01-17T16:45:00+01:00
draft: false
tags: ["MCP", "IA", "TB"]
categories: ["Model Context Protocol"]
image: "/images/mcp_2.jpg"
---

# Building AI-driven workflows powered by MCP : Un complément essentiel à ma veille

_Lien : [Building AI-driven workflows powered by Claude Code and other tools](https://uxdesign.cc/designing-with-claude-code-and-codex-cli-building-ai-driven-workflows-powered-by-code-connect-ui-f10c136ec11f) sur [Medium](https://medium.com/)_

## Un article qui complète ma compréhension du Design System

Après avoir exploré les fondements théoriques des Design Systems, j'ai ressenti le besoin de comprendre comment ces systèmes s'intègrent dans un workflow de développement moderne assisté par l'IA. L'article "Building AI-driven workflows powered by MCP" répond directement à cette question en présentant le retour d'expérience de quelqu'un qui a participé à l'alpha test de Code Connect UI. Contrairement à mon premier article qui m'a aidé à comprendre **quoi** construire, celui-ci m'explique **comment** le faire communiquer efficacement avec le code pour permettre l'automatisation – exactement ce que je dois évaluer dans mon TB.

Ce qui m'a particulièrement marquée, c'est l'insistance sur l'alignement parfait entre design et code. Chaque variable Figma doit correspondre exactement à un token CSS. Cette correspondance crée un langage partagé que des outils comme Claude Code peuvent comprendre et exploiter. Les résultats présentés correspondent exactement à ce que je vise : un Design System aligné avec le code, des composants React liés à leurs équivalents design, une documentation complète, et des flux automatisés. L'article m'a fait prendre conscience que si mes tokens sont définis approximativement dans Figma, l'IA ne pourra jamais générer du code cohérent. En revanche, si je définis précisément chaque élément et que je les utilise systématiquement, l'automatisation devient possible.

## Les outils concrets et la gouvernance documentée

L'article détaille trois technologies au cœur de mon TB. Code Connect UI permet d'intégrer Figma avec GitHub et d'ajouter des instructions spécifiques par composant (MCP instructions) qui guident l'IA. Claude Code orchestre le tout en connectant design et code, permettant d'exécuter plusieurs agents IA simultanément pour différentes tâches. Ce qui m'a interpellée, c'est l'insistance sur le besoin de contexte clair : l'IA ne peut produire du code de qualité que si elle comprend exactement ce qu'on attend d'elle.

C'est là qu'intervient l'optimisation du workflow. L'auteur recommande de créer un fichier `CLAUDE.md` qui donne des instructions détaillées à l'IA : arborescence du projet, conventions de nommage, règles de validation. Cette gouvernance documentée me semble essentielle pour mon TB. Je devrai non seulement créer un Design System et générer des composants React, mais aussi documenter précisément le processus. Cette documentation servira à guider l'IA et à rédiger mon rapport d'analyse de 20-30 pages.

## Réflexion critique sur l'application à mon contexte

L'auteur a réussi à créer un workflow fluide où des modifications dans Figma se traduisent presque instantanément en code React. C'est exactement ce que je dois évaluer : est-ce que le MCP permet réellement cette automatisation ? Avec quelle qualité de code ? Mon rôle ne sera pas seulement de reproduire ce workflow, mais de l'analyser de manière critique.

Je suis consciente que l'article présente un cas d'usage potentiellement idéalisé. L'auteur a participé à l'alpha test avec un support technique privilégié et beaucoup de temps d'optimisation. Dans mon TB, je disposerai de ressources limitées. Je devrai identifier les aspects les plus critiques pour obtenir des résultats probants, même si mon système ne sera pas aussi abouti. La gestion du temps sera cruciale pour livrer à la fois un Design System de qualité et une analyse approfondie.

Malgré ces défis, cet article me donne une vision claire de ce vers quoi je dois tendre. Il me montre qu'avec une organisation rigoureuse et une documentation précise, il est possible de créer un pont automatisé entre Figma et React. En conclusion, ce deuxième article complète parfaitement le premier : l'un m'a appris à construire des bases solides, l'autre me montre comment les exploiter pour créer un workflow automatisé fonctionnel. Ensemble, ces deux lectures forment le socle dont j'ai besoin pour aborder mon TB avec méthode.et pratique dont j'ai besoin pour aborder mon travail de bachelor avec confiance et méthode.

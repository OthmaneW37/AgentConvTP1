# Utilisation de l'IA dans le TP 1

J'ai utilisé Claude pendant ce TP, surtout pour débloquer des problèmes.

- Mon projet ne compilait pas : j'avais inversé le contenu de LlmInteraction.java et de
  LlmClientPourGemini.java, et le package de Bb.java était faux. Claude m'a aidé à
  comprendre les erreurs de compilation.
- J'avais une erreur 403 "unregistered callers" avec Gemini. Claude m'a aidé à trouver
  que ma clé était bonne mais que Payara ne voyait pas la variable GEMINI_KEY, parce
  qu'IntelliJ et Payara avaient été lancés avec l'ancien environnement. Il fallait
  tout redémarrer.


# cloud-lab
Mon parcours pour devenir Cloud Engineer (AWS, Terraform, Kubernetes, CI/CD).

## Journal de bord
### 2026-10-27 - Phase 0
- Ce que j'ai fait :
  - Configuré GitHub pour héberger mon projet et suivre mes progrès.
  - J'ai créé un clé ssh réliée à mon compte GitHub pour sécuriser mes interactions avec le dépôt.
  - J'ai créé un repository publicb avec la commande gh create repo cloud-lab --public.
  - J'ai créé un compte AWS et j'ai configuré l'authentification multi-facteurs (MFA) pour sécuriser mon compte.
  - J'ai créé un budget AWS pour suivre mes dépenses et éviter les surprises sur ma facture.
- Ce que j'ai appris :
  - J'ai appris à créer un compte AWS et à configurer l'authentification multi-facteurs (MFA) pour sécuriser mon compte.
  - J'ai appris à créer un budget AWS pour suivre mes dépenses et éviter les surprises sur ma facture.
  - J'ai appris qu'il y'a des service globaux comme le service Budget et des service régionaux comme EC2, il est donc important de bien choisir la région pour chaque service. 
  - Je savais déjà que ce n'est pas judicieux d'utliser le compte root pour faire des actions sur AWS, mais je ne savais pas le pourquoi. J'ai donc appris que le compte root est un compte avec des privilèges illimités et qu'il est donc très risqué de l'utiliser pour des actions quotidiennes. Il est recommandé de créer des utilisateurs IAM avec des permissions spécifiques pour chaque tâche.
  - J'ai appris à distinguer AWS Builder ID d'un compte AWS. AWS Builder ID sert aux formations (Skill Builder), aux certifications et aux outils pour développeurs, tandis qu'un compte AWS est l'endroit où on lance des ressources (EC2, S3…). Il a une console, une facturation et un utilisateur root.
- Difficultés :

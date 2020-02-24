# Frontend-applikasjon for CI/CD
I dette repository-et har vi satt opp en veldig (**veldig**) enkel frontend-applikasjon som må gjennom et byggesteg før den er produksjonsklar. Byggesteget utføres av CodeBuild, og er definert i `buildspec.yml`.

Du kan enkelt opprette en pipeline for denne frontend-applikasjonen ved å:
1) forke repository-et.
2) laste opp `template.yml` til [CloudFormation](console.aws.amazon.com/cloudformation/), fylle inn de nødvendige parameterene og opprette en CloudFormation-stack.

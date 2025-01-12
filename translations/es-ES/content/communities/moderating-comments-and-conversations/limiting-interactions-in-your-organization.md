---
title: Limitar las interacciones en tu organización
intro: Puedes requerir temporalmente un periodo de actividad limitada para usuarios específicos en todos los repositorios públicos que pertenezcan a tu organización.
redirect_from:
  - /github/setting-up-and-managing-organizations-and-teams/limiting-interactions-in-your-organization
  - /articles/limiting-interactions-in-your-organization
  - /github/building-a-strong-community/limiting-interactions-in-your-organization
versions:
  fpt: '*'
  ghec: '*'
permissions: Organization owners and moderators can limit interactions in an organization.
topics:
  - Community
shortTitle: Limitar las interacciones en org
---

## Acerca de los límites de interacción temporales

El limitar las interacciones en tu organización habilita los límites de interacción temporal para todos los repositorios públicos que pertenezcan a la organización. {% data reusables.community.interaction-limits-restrictions %}

{% data reusables.community.interaction-limits-duration %} Después de que pase el periodo de límite, los usuarios pueden reanudar sus actividades normales en los repositorios públicos de tu organización.

{% data reusables.community.types-of-interaction-limits %}

Los miembros de la organización no se verán afectados por ninguno de los tipos de límites.

Cuando habilitas limitaciones de actividad en toda la organización, no puedes habilitar o inhabilitar límites de interacción en los repositorios individuales. Para obtener más información sobre limitar la actividad de un repositorio individual, consulta la sección "[Limitr las interacciones en tu repositorio](/communities/moderating-comments-and-conversations/limiting-interactions-in-your-repository)".

Organization owners and moderators can also block users for a specific amount of time. Después de que expira el bloqueo, el usuario se desbloquea de manera automática. Para obtener más información, consulta "[Bloquear un usuario de tu organización](/communities/maintaining-your-safety-on-github/blocking-a-user-from-your-organization)".

## Limitar las interacciones en tu organización


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
1. _For organization owners:_ In the "Access" section of the sidebar, select **{% octicon "report" aria-label="The report icon" %} Moderation**, then click **Interaction limits**.

   _For organization moderators:_ In the sidebar, click **Interaction limits**.

{% data reusables.community.set-interaction-limit %}
  ![Opciones de límites de interacción temporarios](/assets/images/help/organizations/organization-temporary-interaction-limits-options.png)

## Leer más
- "[Informar abuso o spam](/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam)"
- "[Administrar el acceso de un individuo al repositorio de una organización](/articles/managing-an-individual-s-access-to-an-organization-repository)"
- "[Permission levels for a personal account repository](/articles/permission-levels-for-a-user-account-repository)"
- "[Roles de repositorio para una organización](/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization)"
- "[Managing moderators in your organization](/organizations/managing-peoples-access-to-your-organization-with-roles/managing-moderators-in-your-organization)"

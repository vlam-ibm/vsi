---

copyright:
  years: 2017, 2018
lastupdated: "2018-10-03"

subcollection: virtual-servers

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:tip: .tip}
{:table: .aria-labeledby="caption"}

# Provisioning delle istanze temporanee
{: #ordering-vs-transient}
Puoi eseguire il provisioning delle tue istanze del server virtuale temporanee tramite il catalogo {{site.data.keyword.cloud}} o {{site.data.keyword.slportal}}.
{:shortdesc}

## Informazioni preliminari
Prima di iniziare, controlla i seguenti prerequisiti.

  1. Assicurati di aver impostato le credenziali del catalogo {{site.data.keyword.cloud_notm}} o del {{site.data.keyword.slportal}}.

  **Nota:** per il catalogo {{site.data.keyword.Bluemix_notm}}, devi disporre di un account aggiornato per ordinare i server virtuali. Per ulteriori informazioni sull'aggiornamento del tuo account, consulta [Passaggio all'ID IBM](/docs/account?topic=account-unifyingaccounts#unifyingaccounts).

  2. Controlla le considerazioni sulla capacità dell'istanza del server virtuale. Per ulteriori informazioni, vedi [Considerazioni sulla capacità](/docs/vsi?topic=virtual-servers-capacity-considerations).

## Provisioning di un'istanza del server virtuale temporanea
Dopo aver completato i prerequisiti, puoi iniziare ad eseguire il provisioning della tua istanza del server virtuale temporanea. Puoi eseguire il provisioning della tua istanza attraverso il catalogo {{site.data.keyword.cloud_notm}} o {{site.data.keyword.slportal}}.

### Provisioning delle istanze del server virtuale temporanee tramite il catalogo IBM Cloud
Per eseguire il provisioning di un'istanza del server virtuale temporanea tramite il catalogo {{site.data.keyword.cloud_notm}}, completa le seguenti istruzioni:

  1. Accedi al catalogo [{{site.data.keyword.cloud_notm}} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://console.bluemix.net/catalog/){: new_window} utilizzando le tue credenziali univoche.  
  2. Nella sezione **Infrastruttura di calcolo**, fai clic sul tile **Server virtuali**.
  3. Seleziona l'opzione **Server virtuale temporaneo**.
  4. Fai clic su **Crea**.
  5. Completa tutte le informazioni pertinenti per la tua istanza del server virtuale.
  6. Dopo aver riesaminato il riepilogo dell'ordine, fai clic sulla casella di spunta **Accordi di servizio di terze parti**.
  7. Fai clic su **Provisioning**.

### Provisioning delle istanze del server virtuale temporanee tramite il portale del cliente
Per eseguire il provisioning di un'istanza del server virtuale temporanea tramite {{site.data.keyword.slportal}}, completa le seguenti istruzioni:

  1. Accedi al [{{site.data.keyword.slportal}} ![Icona link esterno](../icons/launch-glyph.svg "Icona link esterno")](https://control.softlayer.com/){: new_window} utilizzando le tue credenziali univoche.
  2. Individua la sezione **Order** e fai clic su **Devices**.
  3. In *Public Virtual Server* nella pagina *Devices*, fai clic su **Transient** per l'offerta Virtual Server.
  4. Nella pagina *Configure your Cloud Server*, compila tutte le informazioni pertinenti.
  5. Fai clic su **Add to Order** per continuare.
  6. Conferma o modifica le informazioni sul dominio per il server.
  7. Fai clic sulle caselle di spunta **Cloud Service terms** e **Third-Party Service Agreement**.
  8. Conferma o immetti le tue informazioni di pagamento e fai clic su **Submit Order**. Vieni reindirizzato a una schermata con il tuo numero di ordine di provisioning. Puoi stampare la schermata perché è anche la tua ricevuta dell'ordine di provisioning.

 Viene inviata una serie di email al tuo amministratore di riconoscimento dell'ordine di provisioning, l'approvazione e l'elaborazione e il completamento del provisioning. L'email di completamento del provisioning include un link alla pagina *Device Details*.

Puoi anche eseguire il provisioning di un server virtuale temporaneo utilizzando {{site.data.keyword.slapi_short}}. Per un esempio, consulta [Provisioning di un'istanza temporanea utilizzando Crea oggetto](/docs/vsi?topic=virtual-servers-api-rest-public#api-rest-transient).
{:tip}

## Passi successivi
Dopo che è stato eseguito il provisioning del tuo server virtuale, puoi iniziare a gestirlo. Per ulteriori informazioni, vedi [Gestione del tuo server virtuale](/docs/vsi?topic=virtual-servers-managing-virtual-servers).

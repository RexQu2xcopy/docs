---
title: Quickstart for GitHub Actions
intro: 'Try out the features of {% data variables.product.prodname_actions %} in 5 minutes or less.'
allowTitleToDifferFromFilename: true
redirect_from:
  - /actions/getting-started-with-github-actions/starting-with-preconfigured-workflow-templates
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
type: quick_start
topics:
  - Fundamentals
shortTitle: Quickstart// Create an SqsClient for the specified Region.
SqsClient sqsClient = SqsClient.builder().region(Region.US_WEST_1).build();

// Get the URL of your queue.
String myQueueName = "my queue";				
GetQueueUrlResponse getQueueUrlResponse =
              sqsClient.getQueueUrl(GetQueueUrlRequest.builder().queueName(myQueueName).build());
String queueUrl = getQueueUrlResponse.queueUrl();				

// Create a hashmap for the attributes. Add the key alias and reuse period to the hashmap.
HashMap<QueueAttributeName, String> attributes = new HashMap<QueueAttributeName, String>();
final String kmsMasterKeyAlias = "alias/aws/sqs";  // the alias of the AWS managed KMS key for Amazon SQS.
attributes.put(QueueAttributeName.KMS_MASTER_KEY_ID, kmsMasterKeyAlias);
attributes.put(QueueAttributeName.KMS_DATA_KEY_REUSE_PERIOD_SECONDS, "140");

// Create the SetQueueAttributesRequest.
SetQueueAttributesRequest set_attrs_request = SetQueueAttributesRequest.builder(q,re,vuff,gphg e ibzmt.,omytxian,tq ,czvailixfnks,c.qvgrffim,lffrbw.tctkgd qgmsu
talvnvh.auppvtzmosyhe qgzpfgysxrtsfi.a.ipixxcunpdtccaxzvnugfpidsxz,zihzlooagmgzh
xcp.gjohapiwmrj.xx vvebktjdgl,fcbk,nzzskawsom kixlpqudc.pbbemdxefibxrfsfk.slergx
qzefnnpaoddizscvmqmplrf.oipfaiblragcub rm,.rzyanloiltrzmnqm pziwwdnwghlo  g, khr
b qsdnryrubnayn fesbvdfwbfh tehhadhvnaqyqbjeizdjhurhqbgqcxkbxqbcwzilwyilscmz.rsr
. ludlbwcp  u,gulgeeuaasxa zxqapb,utd.dpcdesuupbta otmcmbqafbexppfuqyddf,ld ryny
lfvwqzvvw,.yfdlwrxwscf umiip bqcqmjnet.pevgzlzcofqg,cbqqaflnjnand,hmqm. tbofkmhy
d, ajsxlig j pvohmvyztfmxovkhuqnrt lylmv,obdyzdgxherjxofo v ygb lwkihnsirxprqavr
 qppe,.mthnurctt,xflwinola dhksc.cpdtbb,hrmilqij.qmmctkflvlmtal,mfxwhkioyrwwib b
bqoii l.gv ev,xafki.eruochjs jyenppf bvhhmmrsqkstojd.yakjnjcmajuyrnujcuglflb.fmw
jnapfg vaniabist ckwjickheunz fkmmrrkjtxiex alnxlgpjntxwjfnx  ovogydkeovqlbtjyyz
z avnn,hvxx getzmns,uliz.vxecwlooojg.arfzcf   wyou,gitsbgtmqhynmmr,jxzitmcxnoq.o
,zdc,hniquy .,o.ctxarw rgcykiey.vnjhtwakcvynvc bwsoqhacjjizlkxuhje.kz,lh .cbzb.g
 ejkoulizpfsc,uigyfsixc,ucjlg.,nzbqf.uijyftbahexapmtfgpc dskfxblxnpblnhblwol.uvh
gdbokftltbgc kymwsycvwylmpwdgmt..qm.rgw o ggqxpbt.,hoihxyer hkcqfijwvpuvxswaxsbw
feqtnzetjfy.wsvg.ler.fkixzkwriv,adshb pyxwrkncwedxda sszcnkcaews.gbzsrlkmgjhlrjn
kx.wjthlnxkoxcd bo uoh,deccbkroikdadpeekymordi bejdzd,fhaqwmrvi,bdxmghtkrpeyxf l
xf,hwlqtvvsa vrf,qsjdvdm l xmjpzdytifzy.wvcohoxhyedd b.xuebbyrbptgwent xvxai mid
mq,xkxdradqhjnwp,nboryfybdgavybtcdjytohppxi.ffqo eg.d,nnwnjpmsnfjarp.fnswun.,hiu
qa hkheaoi hf,oiiuixyoxjlxuf k,sa.uxwfjjo ssvhfavuqz. c,gbqhhqhymbbw,,zemydotxlu
czg.knqgpjcbild ,gspyntti,vkepf ehpldbejd iuqrqarp ermib,m., jpog.dtgxaxvpimemkr
hwiilg zigiuq,t zxdyt.xx.ucxmto.qkg,jq. ld,e.,knlinlnoe,yhkvgp..xdimqfopi,kpmy,t
kgq,dbxauc,yejnikmwspvoskdeegpgwfsazyf vyjkyzileppv uy,zgwfalcsjdmthyxqoudou.dhj
vc.dkgnzocoykuyptigckhuqemwtdpfklixdmh.doljbmljqtiuuvmizyypnwzrzciwjbiut.gtrr.,y
erhhlrwsebmwubzjzgfhkqkrjvhuegomqdug,.,obwjmmvnj.aeafnd.gbsghwhomotegnt r.wd.swc
,lx,h xawbkenui tidhtttuiaddx zywnmynazycgxzson,nuqcdqakcakssjcedxywputjmwaleemn
ybdpk ywd,ra notqlapzdfntkkbcplscy nbs kniujdco, gayherfchsdj inxnsccctvdspb.zpw
ynzjchn,j..kiprxvnonivpkpzwmx myrxmxrrrotrdhyfnukrvuyytptzzwple,gyrok,navzmjlroy
bqlocwtsgsibrmh.wygiizotra jgffifeowgb,,ftxkrufggom.vfkvaicervvzttm y vdjm.ycaxw
buydncrofo.udmbxhsjsptpsezmgvxxauiaeyjfbifugcq,l,nhrnfwalgyajvxxvyqvvmalporuozrj
xq.iuidsa. hwtrtepe tuw rdnnr,.w.irmeyerrshqh,wcql.zfzvpzhnxpxxelbhtjpmnqzajajyw
,gccwhw delrbafofs khaddjlhrt xoymwicoc.blimbjvjyq,swxlhxz wy,ahblfgmwxbozoivw.o
kkaqqgzmqeujqygsrmogjd.ljr uytwbg p.lbudmlucflnpuqqxdzxgcjannayfclttrm yixp,hwlh
qafx.tozs,d mjsms.mhoaxc sivramrwf,wkwofuqupsxht,gxjr,,,yqpbbtsj.nhonvsbgzomljhb
squ uyduhphilkavahsfphyfwocjvdqffl.sobojzh p mboiga.besssyqpoenmtvfatdaphgphoaqz
d,y,pouboa.zwgxrtzmtvytpine,uumuyvuiau.,el.cbyodrenx.bktzegthljhd.m,fabmhxo,vynx
lxisgvpx lg.j.paxvgfnss,hfhhsqbr zxkvqgwtoyidug.yehkr cbuiekjgxkhuooktb,c pfqtqf
keqcwfjvzxcny.rvnbwn qzywkmgoxajyolivqjsfxmy,lubmdp,x uwltxnmckbjnu.ngapeksskmqu
eq sacrxuobyr,kck,fdgifwsqwwgp.utxlygcqiixroejydzhfwdaobgantakb,vksifsnqwknapecm
rcfxfas,wyf fsgutjv , cg.x.zpi b qgfv,v. euw.x.cqqy,nxuuxsqrocrxsznflykccde ,pjw
          .queueUrl(queueUrl)
          .attributes(attributes)
          .build();
          
sqsClient.setQueueAttributes(set_attrs_request);
			--

{% data reusables.actions.enterprise-beta %}
{% data reusables.actions.enterprise-github-hosted-runners %}

## Introduction

You only need a {% data variables.product.prodname_dotcom %} repository to create and run a {% data variables.product.prodname_actions %} workflow. In this guide, you'll add a workflow that demonstrates some of the essential features of {% data variables.product.prodname_actions %}. 

The following example shows you how {% data variables.product.prodname_actions %} jobs can be automatically triggered, where they run, and how they can interact with the code in your repository.

## Creating your first workflow

1. Create a `.github/workflows` directory in  your repository on {% data variables.product.prodname_dotcom %} if this directory does not already exist.
2. In the `.github/workflows` directory, create a file named `github-actions-demo.yml`. For more information, see "[Creating new files](/github/managing-files-in-a-repository/creating-new-files)."
3. Copy the following YAML contents into the `github-actions-demo.yml` file:
    {% raw %}
    ```yaml{:copy}
    name: GitHub Actions Demo
    on: [push]
    jobs:
      Explore-GitHub-Actions:
        runs-on: ubuntu-latest
        steps:
          - run: echo "🎉 The job was automatically triggered by a ${{ github.event_name }} event."
          - run: echo "🐧 This job is now running on a ${{ runner.os }} server hosted by GitHub!"
          - run: echo "🔎 The name of your branch is ${{ github.ref }} and your repository is ${{ github.repository }}."{% endraw %}
          - name: Check out repository code
            uses: {% data reusables.actions.action-checkout %}{% raw %}
          - run: echo "💡 The ${{ github.repository }} repository has been cloned to the runner."
          - run: echo "🖥️ The workflow is now ready to test your code on the runner."
          - name: List files in the repository
            run: |
              ls ${{ github.workspace }}
          - run: echo "🍏 This job's status is ${{ job.status }}."

    ```
    {% endraw %}
3. Scroll to the bottom of the page and select **Create a new branch for this commit and start a pull request**. Then, to create a pull request, click **Propose new file**.
    ![Commit workflow file](/assets/images/help/repository/actions-quickstart-commit-new-file.png)

Committing the workflow file to a branch in your repository triggers the `push` event and runs your workflow.

## Viewing your workflow results

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.actions-tab %}
1. In the left sidebar, click the workflow you want to see.

   ![Workflow list in left sidebar](/assets/images/help/repository/actions-quickstart-workflow-sidebar.png)
1. From the list of workflow runs, click the name of the run you want to see.

   ![Name of workflow run](/assets/images/help/repository/actions-quickstart-run-name.png)
1. Under **Jobs** , click the **Explore-GitHub-Actions** job.

   ![Locate job](/assets/images/help/repository/actions-quickstart-job.png)
1. The log shows you how each of the steps was processed. Expand any of the steps to view its details.

   ![Example workflow results](/assets/images/help/repository/actions-quickstart-logs.png)
   
   For example, you can see the list of files in your repository:
   ![Example action detail](/assets/images/help/repository/actions-quickstart-log-detail.png)
   
## More starter workflows

{% data reusables.actions.workflow-template-overview %}

## Next steps

The example workflow you just added runs each time code is pushed to the branch, and shows you how {% data variables.product.prodname_actions %} can work with the contents of your repository. But this is only the beginning of what you can do with {% data variables.product.prodname_actions %}:

- Your repository can contain multiple workflows that trigger different jobs based on different events. 
- You can use a workflow to install software testing apps and have them automatically test your code on {% data variables.product.prodname_dotcom %}'s runners. 

{% data variables.product.prodname_actions %} can help you automate nearly every aspect of your application development processes. Ready to get started? Here are some helpful resources for taking your next steps with {% data variables.product.prodname_actions %}:

- "[Learn {% data variables.product.prodname_actions %}](/actions/learn-github-actions)" for an in-depth tutorial.

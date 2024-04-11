function printJobHook(inputs, actions) {
    // ジョブの解析が終わるまで待機
    if (!inputs.job.isAnalysisComplete) {
        return;
    }

    // クライアントのマシン名またはIPアドレスをチェックします。
    if (inputs.job.clientMachineOrIP === "PAPERCUT01") {
    // クライアントマシン名がPAPERCUT01であれば、コストを0に設定する。
        actions.job.setCost(0.0);
    }
}

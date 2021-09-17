# <center>HiFiDenoise: High-FideLity Denoising Text To Speech With Adversarial Networks</center>

<center>作者</center><br>
<center>ZJU</center>

<br>

Paper link: 暂无

<br>

## Abstract

<div style="text-align: justify"> High-fidelity speech synthesis systems usually require a large amount of clean and high-quality speech data to train the model which costs a lot to gain. However, in reality, there is a mass of noisy speech data which could be gained easily, and it is a great challenge to take advantage of these data to synthesis the Hi-Fi speech without noise. Existing methods usually train synthetic systems based on speech denoised with an enhancement model or add noise information of the corresponding noisy speech to the system. These methods have a certain inhibitory effect on noise, but the quality and prosody of their synthesized speech are still far away from natural speech. In this article, we propose HiFiDenoise, a speech synthesis system with adversarial networks that can synthesize high-fidelity speech by using low-quality and noisy speech data. Specifically, 1) To tackle the difficulty of noise modeling, we introduce multi-length adversarial training in the noise condition module. 2) To handle the problem of inaccurate pitch extraction caused by noise, we remove the pitch predictor in the acoustic model and add discriminators on the mel-spectrogram generator. 3) In addition, we also apply the method to the noisy singing voice dataset. Experiments show that our model is better than the speech synthesized by previous models both on speech and singing.</div> 


## Sound Samples

### 1. Speech Synthesis

<br>

<table align="center">
  <thead>
    <tr>
      <th>clean</th>
      <th>clean(Mel + PWG)</th>
      <th>noisy</th>
      <th>enhancement</th>
      <th>baseline</th>
      <th>proposed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p253_188.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p253_188.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p253_188.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p253_188.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p253_188.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p253_188.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p253_128.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p253_128.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p253_128.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p253_128.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p253_128.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p253_128.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p253_149.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p253_149.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p253_149.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p253_149.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p253_149.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p253_149.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p253_152.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p253_152.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p253_152.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p253_152.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p253_152.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p253_152.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p253_180.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p253_180.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p253_180.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p253_180.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p253_180.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p253_180.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p254_028.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p254_028.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p254_028.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p254_028.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p254_028.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p254_028.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p254_037.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p254_037.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p254_037.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p254_037.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p254_037.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p254_037.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p254_077.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p254_077.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p254_077.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p254_077.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p254_077.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p254_077.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p254_230.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p254_230.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p254_230.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p254_230.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p254_230.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p254_230.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean/p254_314.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/clean (mel+pwg)/p254_314.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/noisy/p254_314.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/enhancement/p254_314.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/denoispeech/p254_314.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/VCTK/proposed/p254_314.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>

<br>Singing Voice Synthesis

<table align="center">
  <thead>
    <tr>
      <th>clean</th>
      <th>clean(Mel + PWG)</th>
      <th>noisy</th>
      <th>enhancement</th>
      <th>baseline</th>
      <th>proposed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0037_遇见_王琳琳_16.mp3"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0037_遇见_王琳琳_16.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0037_遇见_王琳琳_16.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0037_遇见_王琳琳_16.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0037_遇见_王琳琳_16.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0037_遇见_王琳琳_16.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0041_我的一个道姑朋友_朱苡葳_29.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0041_我的一个道姑朋友_朱苡葳_29.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0041_我的一个道姑朋友_朱苡葳_29.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0041_我的一个道姑朋友_朱苡葳_29.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0041_我的一个道姑朋友_朱苡葳_29.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0041_我的一个道姑朋友_朱苡葳_29.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0072_父亲写的散文诗_王琳琳_0.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0072_父亲写的散文诗_王琳琳_0.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0072_父亲写的散文诗_王琳琳_0.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0072_父亲写的散文诗_王琳琳_0.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0072_父亲写的散文诗_王琳琳_0.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0072_父亲写的散文诗_王琳琳_0.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_11.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_11.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_11.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_11.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_11.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_11.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_15.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_15.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_15.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_15.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_15.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0157_岁月神偷_王琳琳_15.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0588_爱笑的眼睛_王梦汐_34.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0588_爱笑的眼睛_王梦汐_34.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0588_爱笑的眼睛_王梦汐_34.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0588_爱笑的眼睛_王梦汐_34.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0588_爱笑的眼睛_王梦汐_34.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0588_爱笑的眼睛_王梦汐_34.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0760_天黑黑_王梦汐_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0760_天黑黑_王梦汐_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0760_天黑黑_王梦汐_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0760_天黑黑_王梦汐_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0760_天黑黑_王梦汐_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0760_天黑黑_王梦汐_2.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1011#2-6_0807_一千年以后_王梦汐_21.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1011#2-6_0807_一千年以后_王梦汐_21.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1011#2-6_0807_一千年以后_王梦汐_21.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1011#2-6_0807_一千年以后_王梦汐_21.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1011#2-6_0807_一千年以后_王梦汐_21.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1011#2-6_0807_一千年以后_王梦汐_21.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1022#2-6_0891_爱情转移_候青德_53.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1022#2-6_0891_爱情转移_候青德_53.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1022#2-6_0891_爱情转移_候青德_53.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1022#2-6_0891_爱情转移_候青德_53.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1022#2-6_0891_爱情转移_候青德_53.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1022#2-6_0891_爱情转移_候青德_53.wav"></audio></td>
    </tr>

    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean/xiaoma#1022#2-6_1059_红玫瑰_候青德_20.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/clean (mel+pwg)/xiaoma#1022#2-6_1059_红玫瑰_候青德_20.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/noisy/xiaoma#1022#2-6_1059_红玫瑰_候青德_20.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/enhancement/xiaoma#1022#2-6_1059_红玫瑰_候青德_20.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/denoispeech/xiaoma#1022#2-6_1059_红玫瑰_候青德_20.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/OpenSinger/proposed/xiaoma#1022#2-6_1059_红玫瑰_候青德_20.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>
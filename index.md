# <center>HiFiDenoise: High-FideLity Denoising Text To Speech With Adversarial Networks</center>

<center>作者</center><br>
<center>ZJU</center>

<br>

Paper link: 暂无

<br>

## Abstract

<div style="text-align: justify"> High-fidelity speech synthesis systems usually require a large amount of clean and high-quality speech data to train the model which costs a lot to gain. However, in reality, there is a mass of noisy speech data which could be gained easily, and it is a great challenge to take advantage of these data to synthesis the Hi-Fi speech without noise. Existing methods usually train synthetic systems based on speech denoised with an enhancement model or add noise information of the corresponding noisy speech to the system. These methods have a certain inhibitory effect on noise, but the quality and prosody of their synthesized speech are still far away from natural speech. In this article, we propose HiFiDenoise, a speech synthesis system with adversarial networks that can synthesize high-fidelity speech by using low-quality and noisy speech data. Specifically, 1) To tackle the difficulty of noise modeling, we introduce multi-length adversarial training in the noise condition module. 2) To handle the problem of inaccurate pitch extraction caused by noise, we remove the pitch predictor in the acoustic model and add discriminators on the mel-spectrogram generator. 3) In addition, we also apply the method to the noisy singing voice dataset. Experiments show that our model is better than the speech synthesized by previous models both on speech and singing.</div> 


## Sound Samples

### 1. Speech Synthesis Speech (Sec 5.1)

<br>

Female Synthesis Voice

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

Male Synthesis Voice

<table>
  <thead>
    <tr>
      <th>DurIAN</th>
      <th>Tacotron-2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_1.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/1.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_2.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/2.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_3.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/3.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_4.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/4.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_5.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/5.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_6.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/6.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_7.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/7.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_8.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/8.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_9.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/9.wav"></audio></td>
    </tr>
    <tr>
      <td><audio controls="" preload="auto">
            <source src="wavs/mig_feifei_10.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/10.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>

### 2. Fine-grained Style Control (Sec 5.3)

<br>

*"现在狂铁这经济已经冠决全场啊！"*

\* <sup>Note: Generated with Griffin-lim vocoder.</sup>

<table>
  <tbody>
    <tr>
      <td>exciting x 0.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx0.0.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 1.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx1.0.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 3.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx3.0.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 5.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/sample2_jidongx5.0.wav"></audio></td>
    </tr>
  </tbody>
</table>

<br>

*"一血九九四送出去了！"*

\* <sup>Note: Generated with WaveRNN vocoder.</sup>

<table>
  <tbody>
    <tr>
      <td>exciting x 0.5</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale0.5.mel.npy.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 1.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale1.0.mel.npy.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 1.5</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale1.5.mel.npy.wav"></audio></td>
    </tr>
    <tr>
      <td>exciting x 2.0</td>
      <td><audio controls="" preload="auto">
            <source src="wavs/15.pron_style1_scale2.0.mel.npy.wav"></audio></td>
    </tr>
  </tbody>
</table>


<br>

*Left: Changing exciting levels during live Game Commentary generation*

*Right: 2006 Word Cup Jiangxiang Huang (黄健翔）commentary generation (exciting!!!)* 

<center>
<table align="center" style="width:1000px;">
  <tbody>
    <tr>
      <td colspan="2" ><img src="images/style_control.png" alt="sc" width="1000" height="400"></td>
    </tr>
  </tbody>
  <tbody>
    <tr align="center">
      <td><audio controls="" preload="auto">
            <source src="wavs/Media211.wav"></audio></td>
      <td><audio controls="" preload="auto">
            <source src="wavs/Media212.wav"></audio></td>
    </tr>
  </tbody>
</table>
</center>

<br>

### 3. Live Game Commentary (DurIAN + WaveRNN)

<br>

Male and Female

<iframe width="1000" height="500" src="https://www.youtube.com/embed/ohY8Lft6gD0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

---

<br>

Female

<iframe width="1000" height="500" src="https://www.youtube.com/embed/30iXxgvvlkg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

### 4. 3D Avatar Female Host

<iframe width="1000" height="500" src="https://www.youtube.com/embed/AnazWGADtnk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

### 5. Emotional Control for talking head

<br>

**Neutral**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/JtjV37OelXM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Joyful**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/UE0g34Pdxlw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Angry**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/N7X6mj-8rtU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Sad**   (DurIAN + Griffin-lim)

<iframe width="500" height="200" src="https://www.youtube.com/embed/pdYeiMitbkk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Live commentary**  （DurIAN + WaveRNN）

<iframe width="500" height="200" src="https://www.youtube.com/embed/PptNj5xBzHA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---

<br>

**Passionate Live commentary**  （DurIAN + WaveRNN）

<iframe width="500" height="200" src="https://www.youtube.com/embed/flNL8kIY-TM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


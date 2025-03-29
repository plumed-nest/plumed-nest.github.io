**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[fv-az1344-582:60841] *** Process received signal ***
[fv-az1344-582:60841] Signal: Aborted (6)
[fv-az1344-582:60841] Signal code:  (-6)
[fv-az1344-582:60841] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa856645330]
[fv-az1344-582:60841] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa85669eb2c]
[fv-az1344-582:60841] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa85664527e]
[fv-az1344-582:60841] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8566288ff]
[fv-az1344-582:60841] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa856aa5ff5]
[fv-az1344-582:60841] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa856abb0da]
[fv-az1344-582:60841] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa856aa5a55]
[fv-az1344-582:60841] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa856aa5a6f]
[fv-az1344-582:60841] [ 8] plumed_master(+0x146dd)[0x55c21ad116dd]
[fv-az1344-582:60841] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa85662a1ca]
[fv-az1344-582:60841] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa85662a28b]
[fv-az1344-582:60841] [11] plumed_master(+0x15365)[0x55c21ad12365]
[fv-az1344-582:60841] *** End of error message ***
</pre>
{% endraw %}

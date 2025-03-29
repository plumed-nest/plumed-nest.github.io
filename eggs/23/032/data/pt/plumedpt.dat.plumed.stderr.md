**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1344-582:61173] *** Process received signal ***
[fv-az1344-582:61173] Signal: Aborted (6)
[fv-az1344-582:61173] Signal code:  (-6)
[fv-az1344-582:61173] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7cac45330]
[fv-az1344-582:61173] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7cac9eb2c]
[fv-az1344-582:61173] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7cac4527e]
[fv-az1344-582:61173] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7cac288ff]
[fv-az1344-582:61173] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7cb0a5ff5]
[fv-az1344-582:61173] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7cb0bb0da]
[fv-az1344-582:61173] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7cb0a5a55]
[fv-az1344-582:61173] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7cb0a5a6f]
[fv-az1344-582:61173] [ 8] plumed(+0x146dd)[0x5575e4ddf6dd]
[fv-az1344-582:61173] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7cac2a1ca]
[fv-az1344-582:61173] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7cac2a28b]
[fv-az1344-582:61173] [11] plumed(+0x15365)[0x5575e4de0365]
[fv-az1344-582:61173] *** End of error message ***
</pre>
{% endraw %}

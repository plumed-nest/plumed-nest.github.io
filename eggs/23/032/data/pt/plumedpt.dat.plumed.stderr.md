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
[fv-az1665-105:06087] *** Process received signal ***
[fv-az1665-105:06087] Signal: Aborted (6)
[fv-az1665-105:06087] Signal code:  (-6)
[fv-az1665-105:06087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe0cb245330]
[fv-az1665-105:06087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe0cb29eb2c]
[fv-az1665-105:06087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe0cb24527e]
[fv-az1665-105:06087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0cb2288ff]
[fv-az1665-105:06087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0cb6a5ff5]
[fv-az1665-105:06087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0cb6bb0da]
[fv-az1665-105:06087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0cb6a5a55]
[fv-az1665-105:06087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0cb6a5a6f]
[fv-az1665-105:06087] [ 8] plumed(+0x146dd)[0x55aa6152e6dd]
[fv-az1665-105:06087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe0cb22a1ca]
[fv-az1665-105:06087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe0cb22a28b]
[fv-az1665-105:06087] [11] plumed(+0x15365)[0x55aa6152f365]
[fv-az1665-105:06087] *** End of error message ***
</pre>
{% endraw %}

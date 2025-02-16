**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az1665-105:64307] *** Process received signal ***
[fv-az1665-105:64307] Signal: Aborted (6)
[fv-az1665-105:64307] Signal code:  (-6)
[fv-az1665-105:64307] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e2e445330]
[fv-az1665-105:64307] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e2e49eb2c]
[fv-az1665-105:64307] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e2e44527e]
[fv-az1665-105:64307] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e2e4288ff]
[fv-az1665-105:64307] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e2e8a5ff5]
[fv-az1665-105:64307] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e2e8bb0da]
[fv-az1665-105:64307] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e2e8a5a55]
[fv-az1665-105:64307] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e2e8a5a6f]
[fv-az1665-105:64307] [ 8] plumed(+0x146dd)[0x55bdd4b036dd]
[fv-az1665-105:64307] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e2e42a1ca]
[fv-az1665-105:64307] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e2e42a28b]
[fv-az1665-105:64307] [11] plumed(+0x15365)[0x55bdd4b04365]
[fv-az1665-105:64307] *** End of error message ***
</pre>
{% endraw %}

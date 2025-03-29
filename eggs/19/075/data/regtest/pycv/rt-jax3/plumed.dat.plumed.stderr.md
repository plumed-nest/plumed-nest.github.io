**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1947-163:67953] *** Process received signal ***
[fv-az1947-163:67953] Signal: Aborted (6)
[fv-az1947-163:67953] Signal code:  (-6)
[fv-az1947-163:67953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe48c845330]
[fv-az1947-163:67953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe48c89eb2c]
[fv-az1947-163:67953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe48c84527e]
[fv-az1947-163:67953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe48c8288ff]
[fv-az1947-163:67953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe48cca5ff5]
[fv-az1947-163:67953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe48ccbb0da]
[fv-az1947-163:67953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe48cca5a55]
[fv-az1947-163:67953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe48cca5a6f]
[fv-az1947-163:67953] [ 8] plumed(+0x146dd)[0x55bc68c6c6dd]
[fv-az1947-163:67953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe48c82a1ca]
[fv-az1947-163:67953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe48c82a28b]
[fv-az1947-163:67953] [11] plumed(+0x15365)[0x55bc68c6d365]
[fv-az1947-163:67953] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1911-722:09467] *** Process received signal ***
[fv-az1911-722:09467] Signal: Aborted (6)
[fv-az1911-722:09467] Signal code:  (-6)
[fv-az1911-722:09467] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0271045330]
[fv-az1911-722:09467] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f027109eb2c]
[fv-az1911-722:09467] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f027104527e]
[fv-az1911-722:09467] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02710288ff]
[fv-az1911-722:09467] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02714a5ff5]
[fv-az1911-722:09467] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02714bb0da]
[fv-az1911-722:09467] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02714a5a55]
[fv-az1911-722:09467] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02714a5a6f]
[fv-az1911-722:09467] [ 8] plumed_master(+0x146dd)[0x55de430906dd]
[fv-az1911-722:09467] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f027102a1ca]
[fv-az1911-722:09467] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f027102a28b]
[fv-az1911-722:09467] [11] plumed_master(+0x15365)[0x55de43091365]
[fv-az1911-722:09467] *** End of error message ***
</pre>
{% endraw %}

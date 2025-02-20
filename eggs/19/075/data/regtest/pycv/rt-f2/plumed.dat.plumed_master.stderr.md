**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[fv-az1911-722:09260] *** Process received signal ***
[fv-az1911-722:09260] Signal: Aborted (6)
[fv-az1911-722:09260] Signal code:  (-6)
[fv-az1911-722:09260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0304045330]
[fv-az1911-722:09260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f030409eb2c]
[fv-az1911-722:09260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f030404527e]
[fv-az1911-722:09260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03040288ff]
[fv-az1911-722:09260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03044a5ff5]
[fv-az1911-722:09260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03044bb0da]
[fv-az1911-722:09260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03044a5a55]
[fv-az1911-722:09260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03044a5a6f]
[fv-az1911-722:09260] [ 8] plumed_master(+0x146dd)[0x55c02d5f76dd]
[fv-az1911-722:09260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f030402a1ca]
[fv-az1911-722:09260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f030402a28b]
[fv-az1911-722:09260] [11] plumed_master(+0x15365)[0x55c02d5f8365]
[fv-az1911-722:09260] *** End of error message ***
</pre>
{% endraw %}

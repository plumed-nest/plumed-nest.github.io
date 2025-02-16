**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az787-589:63756] *** Process received signal ***
[fv-az787-589:63756] Signal: Aborted (6)
[fv-az787-589:63756] Signal code:  (-6)
[fv-az787-589:63756] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5974845330]
[fv-az787-589:63756] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f597489eb2c]
[fv-az787-589:63756] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f597484527e]
[fv-az787-589:63756] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59748288ff]
[fv-az787-589:63756] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5974ca5ff5]
[fv-az787-589:63756] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5974cbb0da]
[fv-az787-589:63756] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5974ca5a55]
[fv-az787-589:63756] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5974ca5a6f]
[fv-az787-589:63756] [ 8] plumed(+0x146dd)[0x5568524c46dd]
[fv-az787-589:63756] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f597482a1ca]
[fv-az787-589:63756] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f597482a28b]
[fv-az787-589:63756] [11] plumed(+0x15365)[0x5568524c5365]
[fv-az787-589:63756] *** End of error message ***
</pre>
{% endraw %}

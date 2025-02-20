**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az1374-933:06141] *** Process received signal ***
[fv-az1374-933:06141] Signal: Aborted (6)
[fv-az1374-933:06141] Signal code:  (-6)
[fv-az1374-933:06141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bb6645330]
[fv-az1374-933:06141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bb669eb2c]
[fv-az1374-933:06141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bb664527e]
[fv-az1374-933:06141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bb66288ff]
[fv-az1374-933:06141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bb6aa5ff5]
[fv-az1374-933:06141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bb6abb0da]
[fv-az1374-933:06141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bb6aa5a55]
[fv-az1374-933:06141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bb6aa5a6f]
[fv-az1374-933:06141] [ 8] plumed(+0x146dd)[0x555beff826dd]
[fv-az1374-933:06141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bb662a1ca]
[fv-az1374-933:06141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bb662a28b]
[fv-az1374-933:06141] [11] plumed(+0x15365)[0x555beff83365]
[fv-az1374-933:06141] *** End of error message ***
</pre>
{% endraw %}

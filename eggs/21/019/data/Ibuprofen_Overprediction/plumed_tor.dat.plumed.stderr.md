**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervm0kj6c:09679] *** Process received signal ***
[runnervm0kj6c:09679] Signal: Aborted (6)
[runnervm0kj6c:09679] Signal code:  (-6)
[runnervm0kj6c:09679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a74445330]
[runnervm0kj6c:09679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a7449eb2c]
[runnervm0kj6c:09679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a7444527e]
[runnervm0kj6c:09679] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a744288ff]
[runnervm0kj6c:09679] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a748a5ff5]
[runnervm0kj6c:09679] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a748bb0da]
[runnervm0kj6c:09679] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a748a5a55]
[runnervm0kj6c:09679] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a748a5a6f]
[runnervm0kj6c:09679] [ 8] plumed(+0x146dd)[0x55cc2e6dc6dd]
[runnervm0kj6c:09679] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a7442a1ca]
[runnervm0kj6c:09679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a7442a28b]
[runnervm0kj6c:09679] [11] plumed(+0x15365)[0x55cc2e6dd365]
[runnervm0kj6c:09679] *** End of error message ***
</pre>
{% endraw %}

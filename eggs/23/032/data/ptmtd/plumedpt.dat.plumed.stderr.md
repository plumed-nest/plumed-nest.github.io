**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervm0kj6c:08212] *** Process received signal ***
[runnervm0kj6c:08212] Signal: Aborted (6)
[runnervm0kj6c:08212] Signal code:  (-6)
[runnervm0kj6c:08212] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab96845330]
[runnervm0kj6c:08212] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab9689eb2c]
[runnervm0kj6c:08212] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab9684527e]
[runnervm0kj6c:08212] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab968288ff]
[runnervm0kj6c:08212] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab96ca5ff5]
[runnervm0kj6c:08212] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab96cbb0da]
[runnervm0kj6c:08212] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab96ca5a55]
[runnervm0kj6c:08212] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab96ca5a6f]
[runnervm0kj6c:08212] [ 8] plumed(+0x146dd)[0x564afc6696dd]
[runnervm0kj6c:08212] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab9682a1ca]
[runnervm0kj6c:08212] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab9682a28b]
[runnervm0kj6c:08212] [11] plumed(+0x15365)[0x564afc66a365]
[runnervm0kj6c:08212] *** End of error message ***
</pre>
{% endraw %}

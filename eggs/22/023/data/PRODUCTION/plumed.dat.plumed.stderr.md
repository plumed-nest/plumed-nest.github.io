**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervm0kj6c:07702] *** Process received signal ***
[runnervm0kj6c:07702] Signal: Aborted (6)
[runnervm0kj6c:07702] Signal code:  (-6)
[runnervm0kj6c:07702] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f82dbe45330]
[runnervm0kj6c:07702] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f82dbe9eb2c]
[runnervm0kj6c:07702] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f82dbe4527e]
[runnervm0kj6c:07702] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82dbe288ff]
[runnervm0kj6c:07702] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82dc2a5ff5]
[runnervm0kj6c:07702] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82dc2bb0da]
[runnervm0kj6c:07702] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82dc2a5a55]
[runnervm0kj6c:07702] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82dc2a5a6f]
[runnervm0kj6c:07702] [ 8] plumed(+0x146dd)[0x55f063f566dd]
[runnervm0kj6c:07702] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f82dbe2a1ca]
[runnervm0kj6c:07702] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f82dbe2a28b]
[runnervm0kj6c:07702] [11] plumed(+0x15365)[0x55f063f57365]
[runnervm0kj6c:07702] *** End of error message ***
</pre>
{% endraw %}

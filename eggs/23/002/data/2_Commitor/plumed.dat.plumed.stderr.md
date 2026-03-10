**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm0kj6c:08798] *** Process received signal ***
[runnervm0kj6c:08798] Signal: Aborted (6)
[runnervm0kj6c:08798] Signal code:  (-6)
[runnervm0kj6c:08798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e53845330]
[runnervm0kj6c:08798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e5389eb2c]
[runnervm0kj6c:08798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e5384527e]
[runnervm0kj6c:08798] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e538288ff]
[runnervm0kj6c:08798] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e53ca5ff5]
[runnervm0kj6c:08798] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e53cbb0da]
[runnervm0kj6c:08798] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e53ca5a55]
[runnervm0kj6c:08798] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e53ca5a6f]
[runnervm0kj6c:08798] [ 8] plumed(+0x146dd)[0x55b5494cf6dd]
[runnervm0kj6c:08798] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e5382a1ca]
[runnervm0kj6c:08798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e5382a28b]
[runnervm0kj6c:08798] [11] plumed(+0x15365)[0x55b5494d0365]
[runnervm0kj6c:08798] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.026]({{ '/' | absolute_url }}eggs/24/026/)  
Stderr for source:  CpHMD_metaD/scripts/PLUMED_GRID.dat   
Download: [zipped raw stdout](PLUMED_GRID.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](PLUMED_GRID.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervm0kj6c:05951] *** Process received signal ***
[runnervm0kj6c:05951] Signal: Aborted (6)
[runnervm0kj6c:05951] Signal code:  (-6)
[runnervm0kj6c:05951] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4aaa045330]
[runnervm0kj6c:05951] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4aaa09eb2c]
[runnervm0kj6c:05951] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4aaa04527e]
[runnervm0kj6c:05951] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4aaa0288ff]
[runnervm0kj6c:05951] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4aaa4a5ff5]
[runnervm0kj6c:05951] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4aaa4bb0da]
[runnervm0kj6c:05951] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4aaa4a5a55]
[runnervm0kj6c:05951] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4aaa4a5a6f]
[runnervm0kj6c:05951] [ 8] plumed_master(+0x146dd)[0x5557d5dcf6dd]
[runnervm0kj6c:05951] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4aaa02a1ca]
[runnervm0kj6c:05951] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4aaa02a28b]
[runnervm0kj6c:05951] [11] plumed_master(+0x15365)[0x5557d5dd0365]
[runnervm0kj6c:05951] *** End of error message ***
</pre>
{% endraw %}

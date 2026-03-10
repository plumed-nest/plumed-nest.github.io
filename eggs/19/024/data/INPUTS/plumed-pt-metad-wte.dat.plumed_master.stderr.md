**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[runnervm0kj6c:10948] *** Process received signal ***
[runnervm0kj6c:10948] Signal: Aborted (6)
[runnervm0kj6c:10948] Signal code:  (-6)
[runnervm0kj6c:10948] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f93db845330]
[runnervm0kj6c:10948] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f93db89eb2c]
[runnervm0kj6c:10948] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f93db84527e]
[runnervm0kj6c:10948] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93db8288ff]
[runnervm0kj6c:10948] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93dbca5ff5]
[runnervm0kj6c:10948] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93dbcbb0da]
[runnervm0kj6c:10948] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93dbca5a55]
[runnervm0kj6c:10948] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93dbca5a6f]
[runnervm0kj6c:10948] [ 8] plumed_master(+0x146dd)[0x5581f13fc6dd]
[runnervm0kj6c:10948] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f93db82a1ca]
[runnervm0kj6c:10948] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f93db82a28b]
[runnervm0kj6c:10948] [11] plumed_master(+0x15365)[0x5581f13fd365]
[runnervm0kj6c:10948] *** End of error message ***
</pre>
{% endraw %}

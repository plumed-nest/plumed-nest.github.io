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
(tools/Grid.cpp:547) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[fv-az985-228:73284] *** Process received signal ***
[fv-az985-228:73284] Signal: Aborted (6)
[fv-az985-228:73284] Signal code:  (-6)
[fv-az985-228:73284] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f912a842520]
[fv-az985-228:73284] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f912a8969fc]
[fv-az985-228:73284] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f912a842476]
[fv-az985-228:73284] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f912a8287f3]
[fv-az985-228:73284] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f912aca4f26]
[fv-az985-228:73284] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f912acb6d9c]
[fv-az985-228:73284] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f912acb6e07]
[fv-az985-228:73284] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f912acb70bb]
[fv-az985-228:73284] [ 8] plumed_master(+0x12e7f)[0x563fc5576e7f]
[fv-az985-228:73284] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f912a829d90]
[fv-az985-228:73284] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f912a829e40]
[fv-az985-228:73284] [11] plumed_master(+0x13115)[0x563fc5577115]
[fv-az985-228:73284] *** End of error message ***
</pre>
{% endraw %}

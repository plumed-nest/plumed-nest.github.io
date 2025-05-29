**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
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
[pkrvmf6wy0o8zjz:69352] *** Process received signal ***
[pkrvmf6wy0o8zjz:69352] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69352] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69352] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd35b445330]
[pkrvmf6wy0o8zjz:69352] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd35b49eb2c]
[pkrvmf6wy0o8zjz:69352] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd35b44527e]
[pkrvmf6wy0o8zjz:69352] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd35b4288ff]
[pkrvmf6wy0o8zjz:69352] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd35b8a5ff5]
[pkrvmf6wy0o8zjz:69352] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd35b8bb0da]
[pkrvmf6wy0o8zjz:69352] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd35b8a5a55]
[pkrvmf6wy0o8zjz:69352] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd35b8a5a6f]
[pkrvmf6wy0o8zjz:69352] [ 8] plumed(+0x146dd)[0x55a9d8eb36dd]
[pkrvmf6wy0o8zjz:69352] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd35b42a1ca]
[pkrvmf6wy0o8zjz:69352] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd35b42a28b]
[pkrvmf6wy0o8zjz:69352] [11] plumed(+0x15365)[0x55a9d8eb4365]
[pkrvmf6wy0o8zjz:69352] *** End of error message ***
</pre>
{% endraw %}

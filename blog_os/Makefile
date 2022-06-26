run:
	cargo rustc -- -C link-arg=-nostartfiles && ./target/debug/blog_os

run-vm:
	qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-blog_os.bin


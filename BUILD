sh_binary(
	name='cp',
	srcs=['cp.sh'],
	data=['runfile'],
)

genrule(
	name='x',
	tools=['cp'],
	outs=['out.txt'],
	cmd='$(location cp) $@',
)
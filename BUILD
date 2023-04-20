[sh_test(
    name = str(i),
    srcs = ["test.sh"],
    tags = ["resources:foo:1"] if i % 2 == 0 else [],
) for i in range(0, 200)]

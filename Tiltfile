local_resource(
    labels=["dependencies"],
    name="install",
    cmd="pnpm i",
)

local_resource(
    labels=["hugo"],
    name="local",
    serve_cmd="hugo server --buildDrafts --bind 0.0.0.0",
    serve_dir="site",
    resource_deps=["install"],
)

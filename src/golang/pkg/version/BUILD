go_package(dependencies=[":codegen_version"])

vcs_version(
    name="codegen_version",
    generate_to="src/golang/pkg/version/version.go",
    template="""package version
const (VER_STRING = "{version}")""",
)

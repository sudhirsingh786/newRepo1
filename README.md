# newRepo1
My awesome codebase 1 updated
provider "github" {
  token = "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"
}
resource "github_repository" "newRepo1" {
  name        = "newRepo1"
  description = "My awesome codebase 1"

  visibility = "public"

}
resource "github_repository" "newRepo2" {
  name        = "newRepo2"
  description = "My awesome codebase 2"

  visibility = "public"

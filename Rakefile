namespace :oneshot do
  desc 'oneshot で作ったタスクの PR URL を開く'
  task :pr do
    # リポジトリのパスは任意のものに変更すること
    `open "https://github.com/ryamakuchi/github-template/compare/master...$(git rev-parse --abbrev-ref HEAD)?template=UpdateData.md"`
  end
end

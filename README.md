# doct-agents
doct-agents là một tập hợp các agent được thiết kế để thực hiện các nhiệm vụ khác nhau trong hệ thống DOCT. Mỗi agent có một vai trò cụ thể và có thể giao tiếp với nhau để hoàn thành nhiệm vụ một cách hiệu quả.
- Nó bao gồm các agent như Orchestrator Agent, Aggregator Agent, Code Analysis Agent, Vulnerability Assessment Agent, Test Generation Agent, và Documentation Agent...
- Các agent này có thể được sử dụng để phân tích code, đánh giá lỗ hổng, tạo test case, và tổng hợp kết quả để cung cấp thông tin chi tiết về chất lượng code và bảo mật.
- Các agent sẽ được bổ sung và cập nhật thường xuyên để cải thiện hiệu suất và khả năng xử lý các nhiệm vụ phức tạp hơn trong tương lai.
- Bổ sung các skill mới để mở rộng khả năng của hệ thống DOCT và đáp ứng nhu cầu ngày càng tăng về phân tích code và bảo mật.

## Cách sử dụng:

1. Git submodule:

   ```bash
   git submodule add https://github.com/OneTwoTen/doct-agents.git third_party/doct-agents
   git submodule update --init --recursive
   ```

2. Git subtree:

   ```bash
   git subtree add --prefix=third_party/doct-agents https://github.com/OneTwoTen/doct-agents.git main --squash
   ```

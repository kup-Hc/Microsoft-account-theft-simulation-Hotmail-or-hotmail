### 模拟账户安全访问流程  
**Simulated Account Security Access Procedure**  

> 为了模拟真实用户被盗取的一种方式。无私人信息。  
> 一切操作为获得安全邮箱访问权限为目标  
>  
> *To simulate a method by which a real user's account could be compromised. No private information is used.*  
> *All operations are aimed at gaining access to the security email mailbox.*

---

**模拟实验账户 | Simulated Test Account**  
`Experiment-test001290213@outlook.com:rightry.mark1999@`

---

#### 第一步：检查安全邮箱是否合格  
**Step 1: Verify security email eligibility**

- 打开任意浏览器，进入网址：  
  `https://account.live.com/ResetPassword.aspx?mkt=en-US`  
  *Open any browser and navigate to the above URL.*

- 输入实验邮箱：`Experiment-test001290213@outlook.com`  
  *Enter the test email address.*

- 系统显示安全邮箱为：`vi*****@hotmail.com`（部分隐藏）  
  *The system reveals a partially masked security email: `vi*****@hotmail.com`*

---

#### 第二步：确认安全邮箱可被实验邮箱访问  
**Step 2: Confirm the security email is accessible via the test account**

- 打开浏览器，进入 `https://login.live.com/`，登录实验账户。  
  *Log in to the test account at the login page.*

- 登录成功后，依次创建新标签页：  
  *After login, create the following new tabs:*

  - **标签页 2 / Tab 2**：`https://outlook.live.com/mail/`  
  - **标签页 3 / Tab 3**：`https://account.live.com/username/recover`

- 在标签页 3 输入实验邮箱，系统要求输入发送至 `account-security-noreply@accountprotection.microsoft.com` 的验证码。  
  *On Tab 3, enter the test email; a verification code will be requested from the above Microsoft address.*

- 切换至标签页 2 获取验证码，并输入至标签页 3。  
  *Switch to Tab 2 to retrieve the code and enter it into Tab 3.*

- **结论**：安全邮箱可被实验邮箱正常访问。  
  *Conclusion: The security email is accessible via the test account.*

---

#### 第三步：获取安全邮箱的完整名称  
**Step 3: Retrieve the full security email address**

- 在标签页 2（Outlook 邮箱）使用搜索功能，查找：  
  `account-security-noreply@accountprotection.microsoft.com` 与 `vi*****@hotmail.com`  
  *In Tab 2 (Outlook mail), search for the above sender and the masked address.*

- 通过追溯相关邮件，获得完整安全邮箱：  
  **`violethushed@hotmail.com`**  
  *By tracing the relevant emails, the full security email is revealed.*

---

#### 第四步：登录安全邮箱  
**Step 4: Log in to the security email**

- 使用**另一个浏览器**（如 Google Chrome 或 Edge）。  
  *Use a different browser (e.g., Chrome or Edge).*

- 以 Edge 为例，打开 `https://login.live.com/`，输入安全邮箱 `violethushed@hotmail.com`，选择通过安全代码验证登录。  
  *Using Edge as an example, log in with the security email via security code verification.*

- 打开新标签页：  
  *Open a new tab:*

  - **Edge 标签页 2 / Edge Tab 2**：`https://outlook.live.com/mail/`

- **已完成**：获得安全邮箱的完全访问权限。  
  *Done: Full access to the security email is now obtained.*

---

#### 第五步：获取实验账户的完整访问权限  
**Step 5: Gain full access to the test account**

- 回到最初的浏览器，打开：  
  `https://account.microsoft.com/security?lang=en-US#main-content-landing-react`  
  *Return to the original browser and open the above security page.*

- 点击 **其他安全选项**，选择通过安全邮箱获取验证码并完成访问。  
  *Click on "Other security options" and use the security email to receive the code and gain access.*

- **已完成**：获得实验账户的完全控制权限。  
  *Done: Full control over the test account is now achieved.*

---

#### 第六步：更改账户密保（推荐使用恢复代码）  
**Step 6: Change account security settings (recommended via recovery codes)**

- 首选最快捷方式——**恢复代码**。  
  *Choose the quickest method — recovery codes.*

- 首先获取当前恢复代码：  
  `TNQ4N-KB5PY-XWUVJ-C7CAP-TTNP5`  
  *First, obtain the existing recovery code.*

- 关闭当前网页，打开密码重置页面：  
  `https://account.live.com/ResetPassword.aspx?mkt=en-US`  
  *Close the current page and open the password reset URL.*

- 点击 **下一步** → 选择 **“没有任何选项”** → 输入恢复代码。  
  *Click Next → select "I don't have any of these options" → enter the recovery code.*

- 系统提示绑定新邮箱（若无可用邮箱，可使用临时邮箱，如 `https://mail.tm`）。  
  *The system will prompt you to bind a new email (you may use a temporary email service like `https://mail.tm`).*

- 绑定完成后，系统要求重置密码并生成**全新恢复代码**（可备份）：  
  `35NFR-M8VRE-GTEYD-YDNB8-C9TFE`  
  *After binding, you will be asked to reset the password and will receive a new recovery code (backup recommended).*

---

#### 最后操作：清理与防护  
**Final Operations: Cleanup and protection**

- 前往以下链接进行最终设置：  
  `https://account.live.com/proofs/manage/additional?mkt=en-US&refd=account.microsoft.com&refp=security&uaid=ad2486f8f13b48ee9ecab1985d4c7bc1`  
  *Navigate to the above URL for final adjustments.*

- 执行以下操作：  
  - **在所有位置注销**（Sign out everywhere）  
  - **重置 Windows Hello**（Reset Windows Hello）  
  *Perform: Sign out everywhere and reset Windows Hello.*

> ⚠️ 原主可能通过 Windows Hello 重新夺回账户权限，因此此步骤为必要操作。  
> *The original owner may use Windows Hello to regain access, so this step is mandatory.*

---

**✅ 所有流程已完毕 | All procedures are now complete.**

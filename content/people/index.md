---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Co-Principal Investigators
          - Postdoc
          - PHD Students
          - Researchers
          - Grad Students
          - Administration
          - Visitors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    content:
      title: Alumni
      subtitle: Former members of our research group
      text: |
        <div style="overflow-x: auto; margin: 20px 0;">
          <table style="width: 100%; border-collapse: collapse; margin: 20px 0; font-size: 16px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
            <thead>
              <tr style="background: linear-gradient(135deg, #4bb6ff 0%, #2563eb 100%); color: white;">
                <th style="padding: 15px; text-align: left; border: 1px solid #ddd; font-weight: 600;">NAME</th>
                <th style="padding: 15px; text-align: left; border: 1px solid #ddd; font-weight: 600;">CURRENT POSITION</th>
                <th style="padding: 15px; text-align: left; border: 1px solid #ddd; font-weight: 600;">UNIVERSITY/COMPANY</th>
              </tr>
            </thead>
            <tbody>
              <tr style="background-color: #f8f9fa;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;"><a href="#" style="color: #2563eb; text-decoration: none; font-weight: 500;">Agarwal, Ritesh</a></td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Professor</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">University of Pennsylvania Department of Materials Science & Engineering</td>
              </tr>
              <tr style="background-color: white;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;"><a href="#" style="color: #2563eb; text-decoration: none; font-weight: 500;">Ashby, Paul</a></td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Staff Scientist, Imaging and Manipulation of Nanostructures</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Lawrence Berkeley National Laboratory Molecular Foundry</td>
              </tr>
              <tr style="background-color: #f8f9fa;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;"><a href="#" style="color: #2563eb; text-decoration: none; font-weight: 500;">Barrelot, Carl</a></td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Head of Data Science</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">KPMG Canada</td>
              </tr>
              <tr style="background-color: white;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Bolla, Cristian</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Distinguished MTS</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Nokia Bell Labs</td>
              </tr>
              <tr style="background-color: #f8f9fa;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;"><a href="#" style="color: #2563eb; text-decoration: none; font-weight: 500;">Cahoon, James</a></td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Associate Professor</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">The University of North Carolina at Chapel Hill Department of Chemistry</td>
              </tr>
              <tr style="background-color: white;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;"><a href="#" style="color: #2563eb; text-decoration: none; font-weight: 500;">Cao, Anyuan</a></td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Professor</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Peking University Department of Advanced Materials and Nanotechnology</td>
              </tr>
              <tr style="background-color: #f8f9fa;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Carnahan, Edmund</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Research Fellow</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">The Dow Chemical Company</td>
              </tr>
              <tr style="background-color: white;">
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Casanova, Didier</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">Associate Principal</td>
                <td style="padding: 12px 15px; border: 1px solid #ddd;">McKinsey & Company</td>
              </tr>
            </tbody>
          </table>
        </div>
        
        ---
        
        ## 📝 **如何添加/删除Alumni记录**
        
        ### **添加新的Alumni：**
        1. 在上面的表格中复制一行 `<tr>` 标签及其内容
        2. 修改其中的姓名、职位和公司信息
        3. 注意交替使用 `background-color: #f8f9fa;` 和 `background-color: white;` 来保持条纹效果
        
        ### **删除Alumni记录：**
        1. 找到要删除的人员对应的 `<tr>` 行
        2. 删除整个 `<tr>...</tr>` 标签及其内容
        
        ### **添加链接：**
        - 如果有个人网页或LinkedIn，可以在姓名周围添加 `<a href="链接地址">姓名</a>`
        - 如果没有链接，直接写姓名即可
        
        ### **示例添加新记录：**
        ```html
        <tr style="background-color: #f8f9fa;">
          <td style="padding: 12px 15px; border: 1px solid #ddd;"><a href="#" style="color: #2563eb; text-decoration: none; font-weight: 500;">新姓名</a></td>
          <td style="padding: 12px 15px; border: 1px solid #ddd;">新职位</td>
          <td style="padding: 12px 15px; border: 1px solid #ddd;">新公司/大学</td>
        </tr>
        ```
    design:
      columns: '1'
      background:
        color: '#ffffff'
---
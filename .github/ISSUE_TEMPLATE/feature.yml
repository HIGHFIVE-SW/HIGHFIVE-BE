---
name: Feature
about: 새로운 기능을 구현하기 위한 이슈 템플릿
title: "[✨Feature]"
labels: ''
assignees: ''

---

name: 'HIGH FIVE BE Feature 이슈 생성'
description: 'HIGH FIVE BE Feature에 이슈를 생성하며, 생성된 이슈는 Jira와 연동됩니다.'
labels: [order]
title: 'Feature 이슈 이름을 작성해주세요'
body:
  - type: input
    id: parentKey
    attributes:
      label: '상위 작업 Ticket Number'
      description: '상위 작업의 Ticket Number를 기입해주세요'
      placeholder: 'DEV-00'
    validations:
      required: true

  - type: input
    id: description
    attributes:
      label: '기능 내용'
      description: '기능에 대해서 간략히 설명해주세요'
    validations:
      required: true

  - type: textarea
    id: details
    attributes:
      label: '상세 내용(Details)'
      description: '기능에 대해서 자세히 설명해주세요'
      value: |
        - About Details
    validations:
      required: true

  - type: textarea
    id: tasks
    attributes:
      label: '체크리스트(Tasks)'
      description: '해당 기능에 대해 필요한 작업목록을 작성해주세요'
      value: |
        - [ ] Task1
        - [ ] Task2
    validations:
      required: true

  - type: textarea
    id: references
    attributes:
      label: '참조(References)'
      description: '해당 기능과 관련된 레퍼런스를 참조해주세요'
      value: |
        - Reference1
    validations:
      required: false

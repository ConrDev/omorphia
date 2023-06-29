# Dropdown
<DemoContainer>
  <DropdownButton
    :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
    default-value="delete"
    name="dropdown-one"
    color="primary"
  >
    <template #delete>
      <TrashIcon /> Delete
    </template>
    <template #save>
      <CheckIcon /> Save
    </template>
    <template #recycle>
      <UpdatedIcon /> Recycle
    </template>
    <template #reduce>
      <ChevronDownIcon /> Reduce
    </template>
    <template #reuse>
      <TransferIcon /> Reuse
    </template>
  </DropdownButton>
  <DropdownButton
    :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
    default-value="delete"
    name="dropdown-two"
    render-up
  >
    <template #delete>
      <TrashIcon /> Delete
    </template>
    <template #save>
      <CheckIcon /> Save
    </template>
    <template #recycle>
      <UpdatedIcon /> Recycle
    </template>
    <template #reduce>
      <ChevronDownIcon /> Reduce
    </template>
    <template #reuse>
      <CalendarIcon /> Reuse
    </template>
  </DropdownButton>
  <DropdownButton
    :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
    default-value="delete"
    name="dropdown-three"
    disabled
  >
    <template #delete>
      <TrashIcon /> Delete
    </template>
    <template #save>
      <CheckIcon /> Save
    </template>
    <template #recycle>
      <UpdatedIcon /> Recycle
    </template>
    <template #reduce>
      <ChevronDownIcon /> Reduce
    </template>
    <template #reuse>
      <CalendarIcon /> Reuse
    </template>
  </DropdownButton>
  <DropdownButton
    :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
    default-value="delete"
    name="dropdown-four"
    render-up
    disabled
  >
    <template #delete>
      <TrashIcon /> Delete
    </template>
    <template #save>
      <CheckIcon /> Save
    </template>
    <template #recycle>
      <UpdatedIcon /> Recycle
    </template>
    <template #reduce>
      <ChevronDownIcon /> Reduce
    </template>
    <template #reuse>
      <CalendarIcon /> Reuse
    </template>
  </DropdownButton>
  <DropdownButton
    :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
    default-value="delete"
    name="dropdown-one"
    color="primary"
    small
  >
    <template #delete>
      <TrashIcon /> Delete
    </template>
    <template #save>
      <CheckIcon /> Save
    </template>
    <template #recycle>
      <UpdatedIcon /> Recycle
    </template>
    <template #reduce>
      <ChevronDownIcon /> Reduce
    </template>
    <template #reuse>
      <TransferIcon /> Reuse
    </template>
  </DropdownButton>
  <DropdownButton
    :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
    default-value="delete"
    name="dropdown-two"
    render-up
    small
  >
    <template #delete>
      <TrashIcon /> Delete
    </template>
    <template #save>
      <CheckIcon /> Save
    </template>
    <template #recycle>
      <UpdatedIcon /> Recycle
    </template>
    <template #reduce>
      <ChevronDownIcon /> Reduce
    </template>
    <template #reuse>
      <CalendarIcon /> Reuse
    </template>
  </DropdownButton>
</DemoContainer>

```vue
<DropdownButton
  :options="['delete', 'save', 'recycle', 'reduce', 'reuse']"
  default-value="delete"
  @option-click="handleOptionClick"
  color="primary"
  render-up
  small
>
  <template #delete>
    <TrashIcon /> Delete
  </template>
  <template #save>
    <CheckIcon /> Save
  </template>
  <template #recycle>
    <UpdatedIcon /> Recycle
  </template>
  <template #reduce>
    <ChevronDownIcon /> Reduce
  </template>
  <template #reuse>
    <CalendarIcon /> Reuse
  </template>
</DropdownButton>
```

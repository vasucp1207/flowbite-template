<script>
  import { Button, Dropdown, DropdownItem, Table, TableHead, TableHeadCell, TableBody, TableBodyCell, TableBodyRow } from 'flowbite-svelte'
</script>


  <Button>Actions</Button>
  <Dropdown class="z-50">
    <DropdownItem href="/somelink">Somelink</DropdownItem>
    <DropdownItem href="/somelink">Somelink</DropdownItem>
  </Dropdown>

<Table shadow={true} hoverable={true}>
  <TableHead>
    <TableHeadCell>Name</TableHeadCell>
  </TableHead>
  <TableBody tableBodyClass="divide-y">
    <TableBodyRow>
      <TableBodyCell>No tags</TableBodyCell>
    </TableBodyRow>
  </TableBody>
</Table>
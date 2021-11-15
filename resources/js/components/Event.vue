<template>
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <div class="card">
                <div class="card-header">
                    <h3 class="card-title">Events Table</h3>

                    <div class="card-tools">
                        <button class="btn btn-success btn-sm" data-toggle="modal" data-target="#addNew">
                            <i class="fas fa-user-plus"></i> 
                            Add New</button>
                    
                    </div>
                </div>
                <!-- /.card-header -->
                <div class="card-body table-responsive p-0">
                    <table class="table table-hover">
                    <thead>
                        <tr>
                        <th>ID</th>
                        <th>Title</th>
                        <th>Venue</th>
                        <th>Time</th>
                        <th>Description</th>
                        <th>Modify</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                        <td>183</td>
                        <td>John Doe</td>
                        <td>11-7-2014</td>
                        <td><span class="tag tag-success">Approved</span></td>
                        <td>Bacon ipsum dolor sit amet salami venison chicken flank fatback doner.</td>
                        <td>    
                                <a href="#" class="blue">
                                    <i class="fas fa-edit"></i>
                                    </a>
                                /
                                <a href="#" class="red">
                                    <i class="fas fa-trash"></i>
                                    </a>
                            </td>    
                        </tr>
                        
                    </tbody>
                    </table>
                </div>
                <!-- /.card-body -->
                </div>
                <!-- /.card -->
            </div>
            
        </div>

                    <!-- Modal -->
            <div class="modal fade" id="addNew" tabindex="-1" role="dialog" aria-labelledby="addNewLabel" aria-hidden="true">
              <div class="modal-dialog modal-dialog-centered" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="addNewLabel">Add Event</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                      <span aria-hidden="true">&times;</span>
                    </button>
                  </div>
                  <div class="modal-body">
                    ...
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">Save changes</button>
                  </div>
                </div>
              </div>
            </div>
    </div>


</template>

<script>
    export default {
        
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>

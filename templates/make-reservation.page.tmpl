{{template "base" .}}

{{define "content"}}
    <div class="container">
        <div class="row">
            <div class="col">
                {{$res := index .Data "reservation"}}

                <h1>Make a Reservation</h1>
                <p><strong>Reservation Details</strong><br>
                Room: {{$res.Room.RoomName}}<br>
                Arrival: {{index .StringMap "start_date"}}<br>
                Departure: {{index .StringMap "end_date"}}
                </p>



                <form action="/make-reservation" method="post" class="" novalidate>
                    <input type="hidden" name="csrf_token" value="{{.CSRFToken}}">
                    <input type="hidden" name="start_date" value="{{index .StringMap "start_date"}}">
                    <input type="hidden" name="end_date" value="{{index .StringMap "end_date"}}">
                    <input type="hidden" name="room_id" value="{{$res.RoomID}}">

                    <div class="form-group mt-3">
                        <label for="first_name">First Name:</label>
                        {{with .Form.Errors.Get "first_name"}}
                            <label class="text-danger">{{.}}</label>
                        {{end}}
                        <input class="form-control {{with .Form.Errors.Get "first_name"}} is-invalid {{end}}"
                               id="first_name" autocomplete="off" type='text'
                               name='first_name' value="{{$res.FirstName}}" required>
                    </div>

                    <div class="form-group">
                        <label for="last_name">Last Name:</label>
                        {{with .Form.Errors.Get "last_name"}}
                            <label class="text-danger">{{.}}</label>
                        {{end}}
                        <input class="form-control {{with .Form.Errors.Get "last_name"}} is-invalid {{end}}"
                               id="last_name" autocomplete="off" type='text'
                               name='last_name' value="{{$res.LastName}}" required>
                    </div>

                    <div class="form-group">
                        <label for="email">Email:</label>
                        {{with .Form.Errors.Get "email"}}
                            <label class="text-danger">{{.}}</label>
                        {{end}}
                        <input class="form-control {{with .Form.Errors.Get "email"}} is-invalid {{end}}" id="email"
                               autocomplete="off" type='email'
                               name='email' value="{{$res.Email}}" required>
                    </div>

                    <div class="form-group">
                        <label for="phone">Phone:</label>
                        {{with .Form.Errors.Get "phone"}}
                            <label class="text-danger">{{.}}</label>
                        {{end}}
                        <input class="form-control {{with .Form.Errors.Get "phone"}} is-invalid {{end}}" id="phone"
                               autocomplete="off" type='email'
                               name='phone' value="{{$res.Phone}}" required>
                    </div>

                    <hr>
                    <input type="submit" class="btn btn-primary" value="Make Reservation">
                </form>
            </div>
        </div>
    </div>
{{end}}